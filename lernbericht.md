# Lern-Bericht
Tuberose - Huschler, Tosuni, Bischof
## Einleitung

In unserem Projekt geht es um eine WPF programmiert Anwendung, welches dazu gebraucht werden kann, Kalorien und Makros zu zählen.

## Was haben wir gelernt?

Wir haben gelernt, wie man bei WPF zwischen den Windows mittels eines Buttons wechseln kann.

## Beschreibung

```csharp
private void speichernButton_Click(object sender, RoutedEventArgs e)
{
    string selectedGoal = ZielBox.SelectedItem.ToString();

    MessageBox.Show("Ausgewählter Wert gespeichert: " + selectedGoal);

    Window1 objWindow1 = new Window1();
    this.Visibility = Visibility.Hidden;
    objWindow1.Show();
}
```


In diesem Code wird beschrieben, was passiert, wenn jemand auf einen "Speichern"-Button klickt.
Zunächst wird der Wert aus einer Dropdown-Liste gesammelt und in einer Variablen gespeichert. 
Dann wird eine Nachricht angezeigt, um zu bestätigen, dass der ausgewählte Wert gespeichert wurde. 
Schliesslich wird ein neues Fenster geöffnet und das aktuelle Fenster ausgeblendet, um das neue Fenster zu zeigen. Zusammengefasst, wenn man den Button klickt, 
wird der ausgewählte Wert gespeichert und ein neues Fenster wird geöffnet.     




![giphy](https://user-images.githubusercontent.com/111046337/230313509-ed1c14d6-bb06-4c02-a42c-89f2f76bfe44.gif)

      
        


## Verifikation

Diese Medien zeigen, wie jeweils der Wechsel von einem Fenster zu einem anderen Fenster. Sie zeigen ausserdem, wie wir diese mit anderen Funktionen 
wie zum Beispiel den Slider kombiniert haben.

# Reflexion zum Arbeitsprozess

Jeder hat das gemacht, was er machen musste. Somit hatten wir keine Probleme, dass jemand zu viel oder zu wenig gemacht hat.

Wir hatten jedoch Probleme uns an WPF zu gewöhnen und somit konnten wir nicht das erreichen, was wir uns in der Planung vorgestellt hatten.

**VBV**: Wir wünschen uns für das nächste Projekt mehr Klarheit in der Kommunikation, da wir manchmal nicht wussten, wer was vom anderen wollte.
Ausserdem müssen wir unseren Prioritäten besser setzen, uns weniger mit dem Layout und mehr mit dem Programmieren beschäftigen.
