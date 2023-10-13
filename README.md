# Klipper Konfiguration für den Anycubic i3 Megs S

![Anycubic i3 Mega S](https://github.com/MacVille/i3Mega-S-Klipper/blob/main/Images/IMG_9937.JPG){width=400 height=600}

## Was wurde an dem i3 Mega S geändert?

| Type               | Änderung                                    | URL                                                                                           |
| ------------------ | ------------------------------------------- | --------------------------------------------------------------------------------------------- |
| X-Carrier          | Umbau auf Anycubic i3 Mega X-Carriage [MK4] | https://www.thingiverse.com/thing:3537449                                                     |
| Druckbettschrauben | Silikon                                     | https://www.amazon.de/Isolierte-3D-Drucker-beheiztes-Nivellierung-Anycubic/dp/B08DLY7JN8?th=1 |
| Extruder Position  |                                             | https://www.thingiverse.com/thing:4753988                                                     |
| BLTouch            |                                             | https://www.amazon.de/ANTCLABS-BLTouch-Smart-Antclabs-BLTouch/dp/B01FFV2TOS                   |
| Firmware           | Knutwurst Custom Firmware                   | https://github.com/knutwurst/Marlin-2-0-x-Anycubic-i3-MEGA-S                                  |
| Stepper Treiber    | TMC2208                                     |                                                                                               |

---

## Warum Klipper?

Am Anfang habe ich natürlich Marlin auf dem Anycubic i3 Mega S genutzt.
Es war auch der Standard, das hat mir über drei Jahre gute Dienste geleistet.
Nach einiger Zeit habe ich auf einen Custom Firmware umgestellt, und zwar auf [Knutwurst](https://github.com/knutwurst/Marlin-2-0-x-Anycubic-i3-MEGA-S)
um auch einen [BLTouch](https://www.amazon.de/ANTCLABS-BLTouch-Smart-Antclabs-BLTouch/dp/B01FFV2TOS) zu nutzen.

Nach der Umstellung von Standard Firmware auf Custom lief der Drucker gut und es gab viele schöne Stunden.

Aber wie alles mal ein Ende hat, war Klipper der neue Anfang :D

Die Möglichkeit jede Einstellung des Druckers anzupassen, fande ich eine gute Möglichkeit mehr über den Drucker zulernen. Was sind die Limits, was kann der Drucker alles machen und was kann er nicht machen.

---

## Inhaltsverzeichnis:

+ [KlipperConfig](/KlipperConfig/config.md)
	+ [includes](/KlipperConfig/includes/includes.md) 
		+ [Area Mesh Macro](/readme.md#area mesh macro)
		+ [BLTouch Einstellungen](/KlipperConfig/includes/bltouch/bltouch.md)
		+ [LED Settings (aktuell nicht in Nutzung)](/KlipperConfig/includes/leds/leds.md)
		+ [Allgemeine Macros](/KlipperConfig/includes/macros/macros.md)
		+ [PID Macros](/KlipperConfig/includes/pid/pid.md)
		+ [Start-, Stop und Purge Macros](/KlipperConfig/includes/start_stop/start_stop.md)


### [Area Mesh Macro](/KlipperConfig/includes/area_mesh/area_mesh.md)

