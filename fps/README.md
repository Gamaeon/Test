# Dämmerzone

Ein Arena-Ego-Shooter im Browser (Three.js, eine einzige HTML-Datei).
Sandstein-Arena im Sonnenuntergang, Drohnen kommen in Wellen.

## Starten

`fps/index.html` in einem Desktop-Browser öffnen (Chrome, Firefox, Edge).
Internet wird für Three.js (cdnjs) und die Schriften (Google Fonts) gebraucht.

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
