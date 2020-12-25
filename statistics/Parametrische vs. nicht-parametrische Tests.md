---
created: 2020-12-25T16:29:34+01:00
modified: 2020-12-25T16:30:35+01:00
---

# Parametrische vs. nicht-parametrische Tests

Parametrische Verfahren setzen bestimmte Voraussetzungen an die Verteilung der Daten (in der Regel muss die Normalverteilungsannahme erfüllt sein).


Nicht parametrische Verfahren unterliegen hingegen keinen Voraussetzungen.


Doch wieso sollte man dann überhaupt parametrische Tests verwenden. Die Ursache hierfür liegt in darin, dass nicht- parametrische Tests eine größere Teststärke aufweisen. Hierunter versteht man


Das Vorgehen ist wie folgt:
- Korrekten Prüffall definieren (2 unabhängige Stichproben, zwei abhängige Stichproben)
- Ausreiser identifizieren und behandeln
- Prüfung der Verteilungsannahme (i.d.R. Normalverteilungsannahme) über geeigneten Test (Shapiro-Wilk Test und der Kolmogorov-Smirnov Test bei Normalverteilung)
- Bei Verletzung der Annahme: vorherige Transformation der Daten (z.B. Logarithmisierung)
- Hilft die Transformation nicht: Bei grosser Stichproben kann der parametrische Test trotzdem verwendet werden. Bei kleinen Stichproben auf nicht parametrische Tests ausweichen