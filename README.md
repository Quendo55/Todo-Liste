# Todo-Liste

Eine Aufgabenliste, die im Browser läuft. Eine einzige HTML-Datei, kein
Installieren, keine Anmeldung.

## Was sie kann

- Aufgaben eintragen — Enter genügt
- abhaken; Erledigtes rutscht nach unten
- Text ändern: die Aufgabe anklicken, tippen, Enter. Escape bricht ab
- Stern für Wichtiges; das wandert nach oben
- Filter: Alle · Offen · Erledigt
- löschen und erledigte Aufgaben auf einmal entfernen — beides lässt sich
  zurückholen
- dunkle Fassung, wenn das Gerät auf dunkel gestellt ist
- auf dem Handy über „Zum Startbildschirm hinzufügen" wie eine App nutzbar

## Wo die Aufgaben liegen

Im Browser auf deinem Gerät (localStorage). Nichts geht ins Internet,
niemand sonst sieht die Liste — auch nicht auf einem anderen Gerät von dir.

## Aufbau

`index.html` hat drei Teile: oben die Farben, in der Mitte der Aufbau der
Seite, unten die Logik. Alles auf Deutsch kommentiert. Es gibt eine Liste
`aufgaben`, in der die Wahrheit steht; jede Aktion ändert sie, speichert
sie und lässt die Seite neu zeichnen.
