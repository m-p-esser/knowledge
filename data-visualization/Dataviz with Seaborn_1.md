---
created: 2020-12-23T23:48:51+01:00
modified: 2020-12-26T15:49:22+01:00
---

# Dataviz with Plotly

## What type of APIs are there?
Plotly.Express is a high level library which abstracts the process of plotting.

## What are they major components in every diagram?

## What are additional notable components?

## How can these components be configured?

## How can plots be saved as flat files, e.g. pngs? 

## Are there predefined colour palettes and diagram backgrounds as in Seaborn?

## How do you proceed when plotting?

fig = px.chart_type(df, parameters)
fig.update_layout(layout_parameters or add annotations)
fig.update_traces(further graph parameters)
fig.update_xaxis() # or update_yaxis
fig.show()

## Where can parameter for a plot be found:
There is an API reference, here is an example for a line plot https://plotly.com/python-api-reference/generated/plotly.express.line.html

## Interesting links: 
https://towardsdatascience.com/visualization-with-plotly-express-comprehensive-guide-eb5ee4b50b57