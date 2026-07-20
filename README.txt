# Immich Backup Manager

![Programmvorschau](docs/programm-vorschau.png)


## Oberfläche / Interface

Die Oberfläche zeigt links die auswählbaren Alben mit Vorschaubildern und rechts die Download-Einstellungen mit Zielordner, Downloadart, Fortschritt und dem blauen **Herunterladen**-Button. Die drei Downloadarten sind direkt auswählbar: **Nur Alben**, **Fotos ohne Album nach Jahr** sowie **Alben + Fotos ohne Album**.

## Deutsch

**Immich Backup Manager** ist ein Windows-Programm zum schnellen Herunterladen von Originalfotos und Originalvideos aus einer Immich-Installation.

Das Programm kann:

- eigene und geteilte Alben herunterladen
- Albumvorschaubilder direkt aus Immich anzeigen
- **Fotos ohne Album nach Jahr** gruppieren und herunterladen
- **alle Fotos mit und ohne Album nach Jahr** gruppieren und herunterladen
- mehrere Alben oder Jahresordner gleichzeitig herunterladen
- Originaldateien ohne ZIP-Archiv sichern
- mehrere Dateien parallel herunterladen
- Fortschritt mit Datei- und Albumzähler anzeigen
- Downloads abbrechen
- vorhandene Dateien vergleichen
- gleich große vorhandene Dateien automatisch überspringen
- bei Konflikten auf Wunsch die größere Datei behalten
- Duplikate zusammenfassen
- Serveradresse und API-Key lokal speichern und den API-Key wieder löschen

### Rechtlicher Hinweis

Dieses Programm ist **Freeware**.

Die Nutzung ist kostenlos. Das Programm ist ein unabhängiges Werkzeug und steht in **keiner Verbindung zum offiziellen Immich-Projekt**.

Copyright © Ralf Ebert. Alle Rechte vorbehalten.

Der Quellcode wird öffentlich zur Transparenz und Nachvollziehbarkeit bereitgestellt. Ohne vorherige schriftliche Genehmigung von Ralf Ebert sind insbesondere nicht erlaubt:

- Verkauf des Programms
- Veröffentlichung geänderter Versionen
- Weitergabe geänderter Quelltexte
- Umbenennung und Veröffentlichung unter anderem Namen
- kommerzielle Verwertung des Programms oder von Teilen davon

Die Nutzung erfolgt auf eigene Gefahr. Es wird keine Haftung für Datenverlust, unvollständige Sicherungen oder sonstige Schäden übernommen.

### Datenschutz

Der API-Key wird nur lokal im Windows-Benutzerprofil gespeichert:

`%APPDATA%\Immich_Backup_Manager\settings.json`

Der gespeicherte API-Key kann im Programm jederzeit gelöscht werden.

### Build unter Windows

1. Rust über `rustup` installieren.
2. Projekt herunterladen oder klonen.
3. `BUILD.cmd` starten.
4. Die fertige EXE heißt: `Immich Backup Manager.exe`

---

## English

**Immich Backup Manager** is a Windows application for fast downloading of original photos and original videos from an Immich installation.

The program can:

- download personal and shared albums
- group and download **photos without an album by year**
- group and download **all photos with and without albums by year**
- download multiple albums or year folders at once
- save original files without ZIP archives
- download multiple files in parallel
- show progress with file and album counters
- cancel downloads
- compare already existing files
- automatically skip files with the same size
- keep the larger version when file conflicts are detected
- merge duplicates
- store the server address and API key locally and delete the API key on request

### Legal notice

This program is **freeware**.

It may be used free of charge. The software is an independent utility and is **not affiliated with the official Immich project**.

Copyright © Ralf Ebert. All rights reserved.

The source code is published for transparency and traceability. Without prior written permission from Ralf Ebert, the following are not permitted:

- selling the software
- publishing modified versions
- redistributing modified source code
- renaming and publishing the software under a different name
- commercial exploitation of the software or parts of it

Use of the software is at your own risk. No liability is accepted for data loss, incomplete backups, or any other damages.

### Privacy

The API key is stored only in the local Windows user profile:

`%APPDATA%\Immich_Backup_Manager\settings.json`

The saved API key can be deleted from within the program at any time.

### Build on Windows

1. Install Rust using `rustup`.
2. Download or clone the project.
3. Run `BUILD.cmd`.
4. The finished executable is: `Immich Backup Manager.exe`
