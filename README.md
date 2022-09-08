# LA1100
# Projekt-Dokumentation

Frei

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|25.08.2022   | 0.0.1   | Heute habe ich Quellen heraus gesucht und an der Projektdokumentation User Stories und Testfälle hinzugefügt.|
|01.09.2022   | 0.0.2   | Ich habe heute die Projektdokumentation überarbeitet und zusätzlich noch researchiert und stopwatch in der Konsole versucht zu intergrieren und zu benutzen.|
|08.09.2022   | 0.0.3   | Ich habe heute die stopwatch zum funktionieren gebracht, einige qualitative Aspekte programmier wie die Ausgabefarben und gestartet mit dem neustart des Programms.|

## 1 Informieren

### 1.1 Ihr Projekt

Eine Konsolenapplikation die von 60 Sekunden im Sekundentakt herunterzählt, jedoch sobald der Benutzer die Entertaste drückt wieder von vorne beginnt.

### 1.2 User Stories

| US-№ | Verbindlichkeit     | Typ            | Beschreibung                                                                                                       |
| ---- | ---------------     | ----           | ----------------------------------                                                                                 | 
| 1    |       Muss          |    Funktional  |Als ein Benutzer möchte ich das Programm starten, damit es von 60 auf 0 herunterzählt.                              |
| 2    |       Muss          |  Funktional    | Als ein Benutzer möchte ich, dass das Programm im Sekundetakt herunter zählt.                                      |
| 3    |       Muss          | Funktional     | Als ein Benutzer möchte ich, dass während das Programm läuft der Text und die einzelnen Zahlen ausgegeben werden.  |
| 4    |       Muss          |  Funktional    | Als ein Benutzer möchte ich die Entertaste drücken, damit das Programm wieder von vorne beginnt herunter zu zählen.|
| 5    |       Kann          |  Qualität      |Als ein Benutzer möchte ich, dass die Konsole die Farbe ändert zu weiss und die Schrift zu schwarz.                 |
| 6    |       Kann          |  Qualität      | Als ein Benutzer möchte ich, dass die Zahlen in der Konsole rot hervorgehoben werden.                              |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |Programm Start| Startbutton| Keine          |
| 2.1  |       1.1    | Keine   | Keine             |
| 3.1  |       2.1    | Keine   | Text              |
| 3.2  |       2.1    | Keine   | Zahlen            |
| 4.1  |Zeit läuft bereits|Entertaste drücken|Neustart der Zeit|
| 5.1  |Programm Start| Keine   | Änderung der Konsolenfarbe|
| 5.2  |Programm Start| Keine   | Änderung der Schriftfarbe|
| 6.1  |Zeit läuft    | Keine   | Zahlen werden Rot gefärbt|


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 01.09.2022      | Simon Frei| Neues Projekt erstellen, researchieren.       |    2 x 45           |
| 1.B  | 01.09.2022      | Simon Frei| Code soll von 60-0 herunterzählen.|    2 x 45 |
| 2.A  | 08.09.2022      | Simon Frei| Code programmieren und anpassen, so dass es im Sekunden Takt herunter zählt.             |      3 x 45         |
| 3.A  | 08.09.2022      | Simon Frei| Text soll richtig ausgegeben werden im richtigen Timing.            |  2 x 45             |
| 3.B  | 15.09.2022      | Simon Frei| Zahlen sollen richtig ausgegeben werden im richtigen Timing.|2 x 45|
| 4.A  | 15.09.2022      | Simon Frei| Bei druck von Entertaste muss das Programm neustarten/von vorne beginnen.| 2 x 45|
| 5.A  | 22.09.2022      | Simon Frei| Konsolenfarbe wird auf weiss gestehlt.| 1/9 x 45|
| 5.B  | 22.09.2022      | Simon Frei| Schriftfarbe wird auf schwarz gestehlt.| 8/9 x 45|
| 6.A  | 22.09.2022      | Simon Frei| Nur die Zahlen die im Sekundentakt ausgegeben werden sollen rot gefärbt werden.| 1 x 45|


## 3 Entscheiden

Ich werde die Applikation mit Hilfe von der  stopwatch funktion programmieren.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |01.09.2022|Simon Frei|2 x 45      |    1.5 x 45      |
| 1.B  |01.09.2022|Simon Frei|2 x 45      |    1.5 x 45      |
| 2.A  |08.09.2022|Simon Frei|3 x 45      |    3 x 45        |
| 3.A  |||||
| 3.B  |||||
| 4.A  |||||
| 5.A  |08.09.2022|Simon Frei|1/9 x 45    |    0.5 x 45      |
| 5.B  |08.09.2022|Simon Frei|8/9 x 45    |    0.5 x 45      |
| 6.A  |||||

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |

✍️ Vergessen Sie nicht, ein Fazit hinzuzufügen, welches das Test-Ergebnis einordnet.

### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |

✍️ Verwenden Sie römische Ziffern für Ihre Bug Reports, also I, II, III, IV etc.

## 6 Auswerten

✍️ Fügen Sie hier eine Verknüpfung zu Ihrem Lern-Bericht ein.
