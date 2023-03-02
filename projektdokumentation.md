# Projekt-Dokumentation

☝️ Alle Text-Stellen, welche mit einem ✍️ beginnen, können Sie löschen, sobald Sie die entsprechende Stellen ausgefüllt haben.

- Gruppe: Tuberose 
- Mitglieder: Bischof, Hurschler, Tosuni

| Datum | Version | Zusammenfassung                                              |
| ----- | ------- | ------------------------------------------------------------ |
|   23.02    | 0.0.1   | Wir haben unser Projekt ausgewählt und User Storys und Diagramme erstellt. |
|       | ...     |                                                              |
|       | 1.0.0   |                                                              |

## 1 Informieren

### 1.1 Ihr Projekt
Wir machen ein Kalorienmanager, den wir mit C# und WPF realisieren.

Unser Projekt ist eine einfach zu bedienen App, welche einem dabei helfen soll, die täglichen Mahlzeiten und Snacks aufzuzeichnen, um zu sehen, wie viele Kalorien, Fette und Proteine eingenommen werden. Man kann ausserdem Workouts aufzeichnen und sehen, wie viele Kalorien verbrennt worden sind. Wir wollen lernen wie man Statistiken und Graphen darstellt.

### 1.2 User Stories

| US-№ | Verbindlichkeit | Typ  | Beschreibung                       |
| ---- | --------------- | ---- | ---------------------------------- |
| 1    |       Muss          |   Qualität   | Als ein Benutzer möchte ich meine Daten, wie Gewicht, Grösse, Alter etc., eingeben, damit ich präzise Vorschläge erhalte. |
|  2    |       Muss          |   Funktional   |Als ein Benutzer möchte ich meine Körperlichen Ziele angeben, damit ich Unterstützung bei genau diesen Zielen bekomme.|
|3|Muss|Funktion|Als ein Computer möchte ich die Angaben und Daten des Benutzers im Hintergrund speichern, damit ich diese für Berechnungen benutzen kann.|
|4|Muss |Funktion |Als ein Computer möchte ich dem Benutzer eine Ansicht bieten, damit er seine Ziele einfach und Benutzerfreundlich auswählen kann.|
|5|Muss |Rand|Als ein Benutzer möchte ich den Kalorienmanager nicht in der Konsole, sondern auf einer übersichtlichen Benutzerfläche nutzen, damit alles einfach und schnell geht. |
|6 |Muss|Funktion|Als ein Computer möchte ich dem Benutzer jederzeit die Möglichkeit bieten, neue Aktivitäten einzutragen, damit er einen möglichst genauen Überblick geniesst. |
|7|Muss |Qualität |Als ein Computer möchte ich eine Grafik erstellen, damit der Benutzer eine Visuelle Zusammenfassung bekommt. |
|8|Muss |Funktion |Als Computer möchte ich die wichtigen Daten im Hintergrund so abspeichern, damit auch nach Schliessen des Kalorienmanagers, alle Daten bestehen bleiben.|
|9|Muss |Funktion|Als ein Computer möchte ich den Kalorienverbrauch mit schon bestehenden Statistiken berechnen, damit der Benutzer keine verfälschten Angaben bekommt.|
|10 |Kann |Qualität | Als Benutzer möchte ich das Design der Kalorienmanagers anpassen (z.B. Dark-Mode), damit auch meine Augen etwas zu geniessen haben. |
|11 |Muss |Rand | Als Benutzer möchte ich das Programm mit der Sprache Deutsch verwenden, damit ich sicher alles verstehe.|
|12 |Muss |Qualität | Als Benutzer möchte ich, dass das Design des Programmes übersichtlich und sauber aussieht, damit ich auch spass daran habe. |
|13 |Muss |Rand | Als ein Computer, möchte ich das Programm in Visual Studios ausführen, weil viele Visual Studios schon haben und es daher leicht zu testen ist. |
✍️ Jede User Story hat eine ganzzahlige Nummer (1, 2, 3 etc.), eine Verbindlichkeit (Muss oder Kann?), und einen Typ (Funktional, Qualität, Rand). Die User Story selber hat folgende Form: *Als ein 🤷‍♂️ möchte ich 🤷‍♂️, damit 🤷‍♂️*.

### 1.3 Testfälle

| TC-№ | Ausgangslage | Eingabe | Erwartete Ausgabe |
| ---- | ------------ | ------- | ----------------- |
| 1.1  |              |         |                   |
| ...  |              |         |                   |

✍️ Die Nummer hat das Format `N.m`, wobei `N` die Nummer der User Story ist, die der Testfall abdeckt, und `m` von `1` an nach oben gezählt. Beispiel: Der dritte Testfall, der die zweite User Story abdeckt, hat also die Nummer `2.3`.

### 1.4 Diagramme

![Abfrage von Daten](https://user-images.githubusercontent.com/111046337/220882427-52ef5f22-b932-4acc-a933-c9e1dd2a9678.png)
![Kalorienseite](https://user-images.githubusercontent.com/111046337/220882448-b2d0cbe1-d126-49ec-85ae-4a1d54208b8c.png)
![Workoutseite](https://user-images.githubusercontent.com/111046337/220882461-303d20db-ac30-4373-be36-e992b3269f04.png)


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
