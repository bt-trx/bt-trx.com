---
layout: post
title: Die nächsten Schritte
#feature-img: "assets/img/about.jpg"
#thumbnail: "assets/img/about.jpg"   # Add a thumbnail image on blog view
tags: []
hide_title: false # Hide the title when displaying the post, but shown in lists of posts
---

Hier ein kleines Update zum Fortschritt des Projekts

## Firmware

Wir hatten zwischenzeitlich wieder die Möglichkeit, die aktuelle Version der
bt-trx Firmware (0.1.0) an weiteren Radiomodellen zu testen. Es zeigt sich, dass
Zubehörradios in der Regel ohne Probleme die Bluetooth Verbindung zu bt-trx
aufbauen. Manche Herstellerradios dahingegen lassen sich aktuell nicht verbinden.
Wir haben bereits ein paar Konfigurationswerte des verwendeten WT32i Bluetooth
Moduls identifiziert, die dieses Problem beheben sollten und werden diese bald
testen.

## Hardware

Aktuell sind wir dabei, die vierte Version des bt-trx Development-Boards zu
entwerfen. Die signifikanteste Änderung ist, dass wir statt des Teensy 3.2
Moduls auf einen ESP32 umsteigen werden. 
Dies machen wir vor allem, weil der ESP32 für ca. die Hälfte des Preises des
Teensy Moduls verfügbar ist. Als weiteren Vorteil bietet der ESP32 integriertes
WLAN, welches wir in Zukunft eventuell für die Konfiguration und Firmwareupdate
des bt-trx nutzen können. Mit dem integrierten Bluetooth LE können wir z.B.
drahtlos einen PTT Button anbinden.

Sobald wir mit der Entwicklung von v4 fertig sind, werden wir uns daran machen,
bt-trx als Bausatz verfügbar zu machen.
