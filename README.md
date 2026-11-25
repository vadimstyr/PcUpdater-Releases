# PC Updater – Downloads

PC Updater hält Treiber, BIOS/Firmware, Programme und Windows aktuell – auf HP-, Dell-, Lenovo- und allen anderen Windows-PCs. Eine einzelne Datei mit Oberfläche: Das Programm erkennt den PC, zeigt die verfügbaren Updates und installiert sie mit einem Klick.

## Herunterladen

**[Neueste Version](https://github.com/vadimstyr/PcUpdater-Releases/releases/latest)** → unter *Assets* `PCUpdater.exe` herunterladen und starten. Die Administrator-Abfrage bestätigen.

- Voraussetzungen: Windows 10 oder 11 und eine Internetverbindung.
- Die EXE ist nicht digital signiert. Windows SmartScreen warnt deshalb eventuell: „Weitere Informationen“ → „Trotzdem ausführen“.
- Zu jeder Version gehört die Datei `PCUpdater.exe.sha256` mit der SHA-256-Prüfsumme.

## Woher die Updates kommen

| Bereich | Quelle |
|---|---|
| Treiber & BIOS – HP | HP Image Assistant |
| Treiber & BIOS – Dell | Dell Command \| Update |
| Treiber & BIOS – Lenovo | Lenovo-Update-Katalog |
| Treiber – alle anderen | Windows Update, inklusive der „optionalen“ Treiber |
| Programme | winget |
| Windows | Windows Update und Microsoft Update |

## Neue Versionen

Ein installierter PC Updater meldet neue Versionen beim Start selbst („Neue Version verfügbar“ → „Jetzt aktualisieren“). Mit „Automatisch aktuell halten“ aktualisiert er sich auch im Hintergrund.

Dieses Repository enthält nur die fertigen Programmdateien.