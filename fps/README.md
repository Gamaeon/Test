# Dämmerzone

Ein Arena-Ego-Shooter im Browser (Three.js, eine einzige HTML-Datei).
Sandstein-Arena im Sonnenuntergang, Drohnen kommen in Wellen.

## Starten

GitHub zeigt die Datei nur als Quellcode an. Zum Spielen:

1. Auf GitHub `fps/index.html` öffnen, oben rechts auf **Download raw file** klicken.
2. Die heruntergeladene `index.html` doppelklicken. Sie öffnet sich im Standard-Browser.

Internet wird für Three.js (cdnjs) und die Schriften (Google Fonts) gebraucht.

Am Handy oder Tablet erscheint automatisch eine Touch-Steuerung: linker Daumen läuft
(virtueller Joystick), rechter Daumen schaut umher, Knöpfe für Feuer, Sprung, Nachladen und Pause.

## Steuerung

| Taste | Aktion |
| --- | --- |
| W A S D | Bewegen |
| Maus / Linksklick | Zielen / Schießen (Dauerfeuer) |
| Shift | Sprinten |
| Leertaste | Springen (auch auf Kisten) |
| R | Nachladen |
| Esc oder P | Pause |

## Inhalt

- Zwei Gegnertypen: **Späher** (schnell, schwach) und **Wächter** (ab Welle 2, zäh, schießt Salven)
- Der leuchtende Kern einer Drohne ist ihr Schwachpunkt (fast dreifacher Schaden, +50 Punkte)
- Rote Reparaturkerne heilen 30 Panzerung; nach 5 s ohne Treffer regeneriert die Panzerung langsam
- Radar, Trefferanzeige, Schadensrichtung, Bestwert (im Browser gespeichert)
- Alle Texturen und Sounds werden prozedural erzeugt, es gibt keine externen Assets
