# Projekt-Dokumentation



- Gruppe: Tuberose 
- Mitglieder: Bischof, Hurschler, Tosuni

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|   09.03.23    | 0.0.1   | Wir haben unser Projekt ausgewählt und User Storys und Diagramme erstellt. |
|   16.03.23    | 0.0.2    |    Wir haben heute das Grundgerüst des Kalorien-Managers geschrieben.                                                          |
|23.03.23       | 0.0.3   | Heute haben wir noch programmiert, was uns gefehlt hat und wir haben gemerkt, dass  wir bei weitem nicht unsere geplanten Pakete erfüllen konnten. Wir hatten jedoch ein Projekt, dass fertig wurde.                                                             |

## 1 Informieren

### 1.1 Ihr Projekt
Wir machen ein Kalorienmanager, den wir mit C# und WPF realisieren.

Unser Projekt ist eine einfach zu bedienen App, welche einem dabei helfen soll, die täglichen Mahlzeiten und Snacks aufzuzeichnen, um zu sehen, wie viele Kalorien, Fette und Proteine eingenommen werden. Man kann ausserdem Workouts aufzeichnen und sehen, wie viele Kalorien verbrennt worden sind. Wir wollen lernen wie man Statistiken und Graphen darstellt.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |       Muss          |   Qualität   | Als ein Benutzer möchte ich meine Daten, wie Gewicht, Grösse, Alter etc., eingeben, damit ich präzise Vorschläge erhalte. |
|  2    |       Muss          |   Funktional   |Als ein Benutzer möchte ich meine Körperlichen Ziele angeben, damit ich Unterstützung bei genau diesen Zielen bekomme.|
|3|Muss|Funktion|Als Benutzer möchte ich, dass meine Daten gespeichert werden, damit Berechnungen für mich gemacht werden können.|
|4|Muss |Funktion |Als Benutzer möchte ich eine Ansicht bekommen, damit ich meine Ziele ganz einfach auswählen kann.|
|5|Muss |Rand|Als ein Benutzer möchte ich den Kalorienmanager nicht in der Konsole, sondern auf einer übersichtlichen Benutzerfläche nutzen, damit alles einfach und schnell geht. |
|6 |Muss|Funktion|Als Benutzer möchte ich jederzeit meine Aktivitäten eintragen, damit ich danach eine Übersciht über meine Tätigkeiten bekommen. |
|7|Muss |Qualität |Als Benutzer will  ich eine Grafik erhalten, damit ich eine Visuelle Zusammenfassung gesiessen kann. |
|8|Muss |Funktion |Als Benutzer will ich, dass alle Ereignisse und Ergebnisse im Hintergrund gespeichert werden, auch wenn das Programm geschlossen ist.|
|9|Muss |Funktion|Als Benutzer will ich keine verfälschten Angaben erhalte. Dafür soll mit den genauen Angaben gerechnet werden.|
|10 |Kann |Qualität | Als Benutzer möchte ich das Design der Kalorienmanagers anpassen (z.B. Dark-Mode), damit auch meine Augen etwas zu geniessen haben. |
|11 |Muss |Rand | Als Benutzer möchte ich das Programm mit der Sprache Deutsch verwenden, damit ich sicher alles verstehe.|
|12 |Muss |Qualität | Als Benutzer möchte ich, dass das Design des Programmes übersichtlich und sauber aussieht, damit ich auch spass daran habe. |
|13 |Muss |Rand | Als Benutzer möchte ich, dass ich das Programm auf meinem Computer läuft. |
|14 |Muss |Qualität | Als Benutzer möchte ich eine klare Anleitung zur Benutzung des Programmes bekommen, damit ich das volle Potential von Programm nutzen kann. |
|15 |Kann |Qualität | Als ein Benutzer möchte ich, dass das Programm einen coolen Namen hat, damit es auch seriös und sauber rüberkommt. |


### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |  Die Applikation startet auf und ein Formular erscheint mit Abfrage von biometrischen Daten.  | Das Gewicht, Grösse und Alter von Benutzer   | Erfolgreiche Eingabe |
| 1.2 |  Das Formular mit der Abfrage von biometrischen Daten startet auf.           | 300 cm   |    Geben sie ihr echtes Grösse ein.   |
| 1.3 |  Das Formular mit der Abfrage von biometrischen Daten startet auf.           | 400 kg   |    Geben sie ihr echtes Gewicht ein.   |
| 2.1 |  Im gleichen Formular sollte eine Auswahl des körperlichen Zieles vorhanden sein.        | Abnehmen  |  Auf der Auswahl steht Abnehmen.  |
| 2.2 |  Im gleichen Formular sollte eine Auswahl des körperlichen Zieles vorhanden sein.        | Zunehmen |  Auf der Auswahl steht Zunehmen.  |
| 3.0 |  Im gleichen Formular sollte eine Auswahl des körperlichen Zieles vorhanden sein.        | Speichern | Angaben wurden erfolgreich gespeichert. |
| 3.0 |  Im gleichen Formular sollte eine Auswahl des körperlichen Zieles vorhanden sein.        | Speichern | Angaben wurden erfolgreich gespeichert. |
| 4.0 |  Das Programm sollte auf einer Benutzeroberfläche laufen     | Soll erscheinen, nachdem auf den Speichern Button gedrückt wurde | Schön gestaltete Seite |
| 5.0 |  Benutzerfreundlich gestaltet Seite startet auf mit dem Kalorienmanager als erst Ansicht        | Soll erscheinen, nachdem auf den Speichern Button gedrückt wurde | Schön gestaltete Seite |
| 5.0 |  Benutzerfreundlich gestaltet Seite startet auf mit dem Kalorienmanager als erst Ansicht        | Soll erscheinen, nachdem auf den Speichern Button gedrückt wurde | Schön gestaltete Seite |
| 6.0 |  Ein Button sollte zu einer Seite führen, in welcher man seine Aktivitäten einschreiben kann und die verbrauchten Kalorien     | soll erscheinen, nachdem auf den Aktivität-Button gedrückt wurde | Ausgabe der Seite mit den Aktivitäten|
| 7.0 |  In jeder externen Seite sollte ein Button sein, welches zum Home Menü führt, in welcher eine grafische Übersicht zu sehen ist   | Soll erscheinen, nachdem auf den Home Button gedrückt wurde | Ausgabe der Home Seite|
| 8.0 |  Das Programm wird geschlossen und wieder aufgestartet  | Aufstarten des Programmes | Ausgabe der Home Seite mit den abgespeicherten Daten von diesem Tag|
| 9.0 |  Im Programm sollte es eine Seite mit verschiedenen Statistiken haben.  | Klick auf die Statistik Button| Ausgabe von verschiedenen Statistiken die berechnet worden sind|
| 10.0 |  Im Programm sollte es einen Dark Mode Modus geben welchen man aktivieren kann  | Klick auf die Dark Mode Button| Änderung der Benutzeroberfläche auf Dunkle Erscheinung.|



### 1.4 Diagramme
![Use case diagram](https://user-images.githubusercontent.com/111046337/222399133-2b511abd-efc5-450d-98de-21618e4e328c.png)
![Abfrage von Daten](https://user-images.githubusercontent.com/111046337/220882427-52ef5f22-b932-4acc-a933-c9e1dd2a9678.png)
![Kalorienseite](https://user-images.githubusercontent.com/111046337/220882448-b2d0cbe1-d126-49ec-85ae-4a1d54208b8c.png)
![Workoutseite](https://user-images.githubusercontent.com/111046337/220882461-303d20db-ac30-4373-be36-e992b3269f04.png)


## 2 Planen

| AP-№ | Frist | Zuständig | Beschreibung | geplante Zeit |
| ---- | ----- | --------- | ------------ | ------------- |
| 1.A  | 02.03.23     |Janick           | Benutzeroberfläche für den Start des Programmes erstellen.            |45 min               |
| 1.B  |02.03.23 | Blentin         |Vorschläge für den Benutzer umschreiben und einfügen.             |45 min               |
| 2.A  |02.03.23 | Gabriel          |Eingabemöglichkeit für den Benutrzer --> seine Ziele auswählen.|45 min               |
| 3.A  |09.03.23 | Blentin, Janick          |Angaben werden im Hintergrund gespeichert für die Berechnung.             |45 min               |
| 3.B |09.03.23 | Blentin, Janick          |Angaben werden im Hintergrund gespeichert für die Berechnung.             |45 min               |
| 4.A  |09.03.23 | Gabriel          |Ansicht             |45 min               |
| 5.A  |09.03.23 | Gabriel          |Kalorienmanager auf einer übersichtlichen Benutzerfläche.             |45 min               |
| 6.A  |09.03.23 | Gabriel          |Neue Aktivitäten können eingetragen werden.           |45 min               |
| 7.A  |09.03.23 | Blentin, Janick        |Grafik         |45 min               |
| 8.A  |16.03.23 | Janick          |Daten werden abgespeichert.              |45 min               |
| 8.B  |16.03.23 | Gabriel         |Nach dem Schliessen bleiben die Daten gespeichert.             |45 min               |
| 9.A  |16.03.23 | Blentin         |Kalorienverbrauch berechnen          |45 min               |
| 9.B |16.03.23 | Blentin        |Kalorienverbrauch berechnen            |45 min               |
| 10.A |16.03.23 | Blentin        |Kalorienverbrauch berechnen            |45 min               |
| 11.A  |16.03.23 | Janick          |Sprache auf Deutsch übersetzen.             |45 min               |
| 12.A  |16.03.23 | Gabriel    |Design            |45 min               |
| 12.B  |16.03.23 | Gabriel          |Design            |45 min               |
| 13.A  |16.03.23       |Janick           |Programm soll in Visual Studio ausgeführt werden.              |45 min               |
| 14.A  |23.03.23 | Janick, Blentin        |Anleitung             |45 min               |
| 14.B  |23.03.23 | Gabriel      |Anleitung             |45 min               |
| 15.A  |23.03.23 | Gabriel       |Name         |5 min               |

Total: 905 min



## 3 Entscheiden



## 4 Realisieren

| AP-№ | Datum | Zuständig | geplante Zeit | tatsächliche Zeit |
| ---- | ----- | --------- | ------------- | ----------------- |
|  1.A |   09.03.23  |    Janick       |       45 min        |        120 min           |
| 1.B  |   09.03.23    |     Blentin      |       45 min        |          120 min         |
 2.A  |   09.03.23    |     Gabriel      |       45 min        |          120 min         |
| 3.A  |   09.03.23    |     Blentin, Janick      |       45 min        |          45 min         |
| 3.B  |   09.03.23    |     Blentin, Janick      |       45 min        |          45 min         |
| 4.A  |   09.03.23    |     Janick      |       45 min        |          45 min         |
| 5.A  |   16.03.23    |     Gabriel      |       45 min        |          45 min         |
| 6.A  |   16.03.23    |     Blentin    |       45 min        |          45 min         |
| 7.A  |   23.03.23    |     Blentin, Janick      |       45 min        |          45 min         |
| 8.A  |   23.03.23    |     Gabriel      |       45 min        |          45 min         |

## 5 Kontrollieren

### 5.1 Testprotokoll

| TC-№ | Datum | Resultat | Tester |
| ---- | ----- | -------- | ------ |
| 1.1  |       |          |        |
| ...  |       |          |        |


### 5.2 Exploratives Testen

| BR-№ | Ausgangslage | Eingabe | Erwartete Ausgabe | Tatsächliche Ausgabe |
| ---- | ------------ | ------- | ----------------- | -------------------- |
| I    |              |         |                   |                      |
| ...  |              |         |                   |                      |



## 6 Auswerten
https://github.com/Blentin05/LA_1500/blob/main/lernbericht.md
