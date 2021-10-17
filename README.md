# Arkanoid
Game Engines Vorlesung Aufgabe Nr. 1 - Arkanoid

Das Spiel besitzt verschieden farbige Steine mit verschiedener Anzahl an Leben. Das bedeutet, dass Steine mit einer höherern Anzahl an Leben öfter getroffen werden müssen.
Rote und Gelbe Steine besitzen ein Leben. Türkisene Steine besitzen zwei und Lilane Steine drei Leben.
Wird ein Stein mit mehr als einem Leben getroffen, wird dieser Dunkler als seine Grundfarbe. 

Das Paddle kann mit den Pfeiltasten der Tastatur sowie den Tasten A und D gesteuert werden. 

Wird ein Stein zerstört, wird mit einer Wahrscheinlichkeit von 30% ein zufälliges Powerup fallen gelassen. Diese Powerups können mit dem Paddle eingesammelt werden.

Vorhandene Powerups im Spiel:
  - Grün: Der Ball wird schneller
  - Blau: Das Paddle wird größer
  - Rosa: Das Paddle wird schneller
  - Rot: Der Ball zerstört einen Stein bei einer Kollision direkt, egal wie viele Leben dieser noch hat und er verändert seine Richtung dabei nicht

Wird ein Stein mit einem Leben zertört sammelt man 100 Punkte. Für das Zerstören eines Steins mit zwei Leben bekommt man 300 Punkte und für das Zerstören eines Steins mit 3 Leben bekommt man 500 Punkte. 
Das Einsammeln eines Powerups wird mit 50 Punkten belohnt.
