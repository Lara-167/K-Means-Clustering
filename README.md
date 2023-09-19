# K-Means-Clustering

#Projektname: K-Means-Clustering

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Lara-167/K-Means-Clustering/HEAD)

#Projektbeschreibung: Für dieses Projekt werden wir versuchen K Means Clustering zu verwenden, um Universitäten in den USA in zwei Gruppen zu unterteilen: Private und öffentliche.
Ein wichtiger Hinweis gleich zu beginn: Für diese Universitäten wissen wir die tatsächliche Zuordnung und finden sie im Datensatz. Wir werden sie aber ignorieren da K Means Clustering ein Unsupervised Learning Algorithmus ist. Normalerweise verwendet man den K Means Clustering Algorithmus für Daten, deren Zugehörigkeit zu einem Cluster man nicht kennt. In diesem Fall verwenden wir die Zuteilung, um beurteilen zu können, wie gut der Algorithmus performt. Da das in echten Anwendungen nicht möglich ist sind Confusion Matrix und Classification Report am Ende des Projekts nur theoretische Auswertungen.

#Der Datensatz beinhaltet folgende Eigenschaften:

    Private: Dummy Varaible mit "Yes" für private und "No" für öffentliche Einrichtungen
    Apps: Anzahl an erhaltenen Bewerbungen
    Accept: Anzahl an angenommenen Bewerbungen
    Enroll: Anzahl neu eingeschriebener Studenten
    Top10perc: Prozent der neuen Studenten der Top 10% einer High School Klasse
    Top25perc: Prozent der neuen Studenten der Top 25% einer High School Klasse
    F.Undergrad: Anzahl an Vollzeitstudenten
    P.Undergrad: Anzahl an Teilzeitstudenten
    Outstate: Gebühr für Studenten, die aus einem anderen Staat kommen
    Room.Board: Kosten für Räume und Mitarbeiter
    Books: Geschätze Kosten für Bücher
    Personal: Geschätzte persönliche Ausgaben
    PhD: Prozent der Fakultäten mit Ph.D.'s
    Terminal: Prozent der Fakultäten mit Terminal Degree
    S.F.Ratio: Rate der Studenten pro Fakultät
    perc.alumni: Prozent der Alumni die spenden
    Expend: Verwaltungskosten pro Student
    Grad.Rate: Abschlussrate

#Code-Ausführung: #GitHub URL des Repository "Logistic-Regression" in https://mybinder.org/ einfügen und launchen 
#Notebook öffnen 
#Code-Zeilen nacheinander ausführen lassen 
#Future Warning ist eine Warninformation und gilt für zukünftige Versionen.

#Code-Abfolge: 
1. Libraries importieren (nachdem sie vorab durch binder installiert wurden)
2. Daten einlesen
3. Explorative Datenanalyse
4. K Means Cluster erstellen
5. Vorhersagen und Auswertung

#Projektergebnis: 
#Es ist mit einer Accuracy von 0.78 zu rechnen. #Damit sind 78% der Vorhersagen der Modelle korrekt. 
#Der Klassifizierungsreport zeigt die Genauigkeit des Modells, um Universitäten in den USA in zwei Gruppen einteilen zu können: Private und öffentliche
