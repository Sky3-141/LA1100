# LA1100
# Projekt-Dokumentation

Frei

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|25.08.2022   | 0.0.1   | Heute habe ich Quellen heraus gesucht und an der Projektdokumentation User Stories und Testfälle hinzugefügt.|

## 1 Informieren

### 1.1 Ihr Projekt

Eine Konsolenapplikation die von 60 Sekunden im Sekundentakt herunterzählt, jedoch sobald der Benutzer die Entertaste drückt wieder von vorne beginnt.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |       Muss          |    Funktional | Muss von 60 auf 0 herunterzählen können.|
| 2    |       Muss          |  Funktional    | Muss im Sekundentakt herunterzählen.|
| 3    |       Muss          | Funktional     | Soll Text und die einzelnen Zahlen ausgeben. |
| 4    |       Muss          |  Funktional    | Muss neustarten wenn die Entertaste gedrückt wird.|
| 5    |       Kann         |  Qualität    | Die Konsole soll zu beginn der Applikation die Farbe zu weiss ändern und die Schrift zu schwarz.|
| 6    |       Kann       |  Qualität    | Die Konsole soll die Farbe der Zahlen die heruntergezählt werden rot färben. |


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

### 1.4 Diagramme

✍️ Hier können Sie PAPs, Use Case- und Gantt-Diagramme oder Ähnliches einfügen.

## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  |       |           |              |               |
| ...  |       |           |              |               |

Total: 

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, auf die sich das Arbeitspaket bezieht, und `m` von `A` an nach oben buchstabiert. Beispiel: Das dritte Arbeitspaket, das die zweite User Story betrifft, hat also die Nummer `2.C`.

✍️ Ein Arbeitspaket sollte etwa 45' für eine Person in Anspruch nehmen. Die totale Anzahl Arbeitspakete sollte etwa Folgendem entsprechen: `Anzahl R-Sitzungen` ╳ `Anzahl Gruppenmitglieder` ╳ `4`. Wenn Sie also zu dritt an einem Projekt arbeiten, für welches zwei R-Sitzungen geplant sind, sollten Sie auf `2` ╳ `3` ╳`4` = `24` Arbeitspakete kommen. Sollten Sie merken, dass Sie hier nicht genügend Arbeitspakte haben, denken Sie sich weitere "Kann"-User Stories für Kapitel 1.2 aus.

## 3 Entscheiden

✍️ Dokumentieren Sie hier Ihre Entscheidungen und Annahmen, die Sie im Bezug auf Ihre User Stories und die Implementierung getroffen haben.

## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
| 1.A  |       |           |               |                   |
| ...  |       |           |               |                   |

✍️ Tragen Sie jedes Mal, wenn Sie ein Arbeitspaket abschließen, hier ein, wie lang Sie effektiv dafür hatten.

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
