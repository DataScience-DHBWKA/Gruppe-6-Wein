# Gruppe-6-Wein
Jan &amp; Vanessa 
Wein-Datensatz:
    • Datenquellen:
        ○ UCI Machine Learning Repository: Wine Quality - UCI Machine Learning Repository
        ○ Kaggle: Red Wine Quality
    • Datensätze:
        ○ Roter Wein: 1600 Zeilen
        ○ Weißer Wein: 4900 Zeilen
    #	Variable	Typ	Skalenniveau	Beschreibung	Kategorie
    1	Fixed acidity	Kommazahl	Metrisch (Verhältnis)	Menge an nichtflüchtigen Säuren wie Weinsäure	Input
    2	Volatile acidity	Kommazahl	Metrisch (Verhältnis)	Menge an flüchtigen Säuren, die Essigsäure enthalten (zu hohe Werte führen zu Essiggeruch)	Input
    3	Citric acid	Kommazahl	Metrisch (Verhältnis)	Natürlich vorkommende Zitronensäure, die Frische verleiht	Input
    4	Residual sugar	Kommazahl	Metrisch (Verhältnis)	Verbleibender Zucker nach der Gärung (höhere Werte machen den Wein süßer)	Input
    5	Chlorides	Kommazahl	Metrisch (Verhältnis)	Salzgehalt im Wein (kann Geschmack und Qualität beeinflussen)	Input
    6	Free sulfur dioxide	Ganzzahl	Metrisch (Verhältnis)	Freies Schwefeldioxid, das als Konservierungsmittel wirkt und Oxidation verhindert	Input
    7	Total sulfur dioxide	Ganzzahl	Metrisch (Verhältnis)	Gesamtmenge an Schwefeldioxid, einschließlich der gebundenen und freien Anteile	Input
    8	Density	Kommazahl	Metrisch (Verhältnis)	Dichte des Weins, beeinflusst durch Zucker, Alkohol und andere gelöste Stoffe	Input
    9	pH	Kommazahl	Metrisch (Verhältnis)	Maß für die Säure eines Weins (niedrige Werte bedeuten höhere Säure)	Input
    10	Sulphates	Kommazahl	Metrisch (Verhältnis)	Sulfatgehalt, kann als Antioxidans wirken und den Geschmack beeinflussen	Input
    11	Alcohol	Kommazahl	Metrisch (Verhältnis)	Alkoholgehalt in Prozent, beeinflusst den Körper und Geschmack des Weins	Input
    12	Quality	Ganzzahl (0-10)	Ordinal	Sensorische Bewertung der Weinqualität (höhere Werte = bessere Qualität)	Output
    • 
Zeitplan:
    • Projektstart: 4. Februar
    • Gesamtdauer: 8 Wochen
Meilensteine:
    • Heute (4. Februar): Projektstart
    • 18. Februar: Erste Präsentation (unbenotet) – Vorstellung der Fragestellung und Vorgehensweise
    • 31. März: Abschlusspräsentation
    • 6. April: Abgabe des Projekts
Projektphasen:
    1. Data Understanding
    2. Business Understanding
3-4. Data Cleaning
5-6. Modelling
    7. Evaluation
    8. Pufferzeit (Pufferzeit im Kanban Board regelmäßig eintragen)

SMART-Ziel:
    • Spezifisch:
        ○ Bestmögliche Vorhersage bei ungesehene Testdaten 
        ○ Interference: wie hängen unterschiedliche chemische Komponenten mit der Qualität zusammen
    • Messbar:
        ○ Bestes Modell, anhand der Bewertung von MSE, R^2 und F1
    • Erreichbar:
        ○ Durchführung von Datenvorverarbeitung, Feature Selection und Ausreißererkennung zur Optimierung der Trainingsdaten
        ○ Anwendung einer Interferenzanalyse, um den Zusammenhang der Variablen zu erkennen
        ○ Hyperparameteranpassung, um die Fehler zu minimieren
        ○ Vergleich mehrerer Modelle, um das beste Modell zu identifizieren
    • Realistisch:
        ○ Der Datensatz enthält ausreichend Zeilen und alle Inputvariablen sind quantitativ.
        ○ Keine fehlenden Werte und keine Duplikate, was die Vorverarbeitung erleichtert.
        ○ Modelle wie lineare Regression und Random Forest sind für diese Aufgabe geeignet.
    • Zeitgebunden:
        ○ Das Projekt wird innerhalb von 7 Wochen abgeschlossen, inkl. einer 1-wöchigen Pufferzeit für Feintuning und Präsentation der Ergebnisse.

Regression 
Knn
Klassen oder regression 

Literatur:
    • Original: wineForTheWin/Cortez_et_al._2009.pdf at master · GeJulia/wineForTheWin
    • Paper 1: (PDF) Using Data Mining for Wine Quality Assessment
    • Paper 2:  wine5.pdf
    • Website: Vinho Verde
    • Analyse von anderen: 
        ○ Red Wine Quality Prediction Using Regression Modeling and Machine Learning | Towards Data Science
        ○ Predicting Wine Quality with Several Classification Techniques | Towards Data Science
    • Repo mit Code: wine_quality_data/Wine Quality Analysis.ipynb at master · simonneutert/wine_quality_data

Bewertungskriterien:
    • Wissenschaftliche Quellen: Umfangreiche und qualitativ hochwertige Quellenangaben
    • Crisp-DM: Klare Darstellung der angewandten Methoden
    • Maschinelles Lernen: Einsatz mehrerer und geeigneter Modelle
    • Fehlerbewertung: Verschiedene und passende Fehlermetriken
    • Evaluation und Begründung: Ausführliche Bewertung und fundierte Argumentation
    • Optimierungspotential: Reflexion über Verbesserungsmöglichkeiten
Weitere Bewertungskriterien:
    • Aufbau und Struktur: Sachliche Gliederung, Logik, fachliche Korrektheit, Zielorientierung
    • Sprachliche Gestaltung: Ausdrucksweise, Satzbau, Stil
    • Zielgruppengerechte Darstellung: Medieneinsatz, Visualisierung, Körpersprache
    • Fachliche Kompetenz: Beherrschung des relevanten Fachhintergrundes
    • Problemerfassung und -lösung: Klare Problemdarstellung und -lösung
    • Argumentation und Begründung: Fundierte und nachvollziehbare Argumente

Inhalt des Berichts & der Endpräsentation:
    • Beschreibung des Datensatzes: 
    • Kontext und Ziel des Projekts
    • Explorative Datenanalyse
    • Anwendung von Machine Learning Methoden (Regression oder Klassifikation)
    • Vergleich der Modelle, Evaluation und Diskussion der Ergebnisse

Business Understanding:
    • Forschungsfragen: Welche Fragen wurden formuliert und welche Erkenntnisse gewonnen? Wo können wir ansetzen?
    • Plattformen: Wurde der Datensatz bereits auf anderen Plattformen analysiert?
    • Relevanz: Warum ist dieses Thema wichtig und für wen?



