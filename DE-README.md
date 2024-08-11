# streamer analytics

## Installationsanleitung
1. Bevorzugte Version aus den oben genannten Verzeichnissen herunterladen
    - Es wird empfohlen, die neueste Version zu verwenden.
2. Dateien extrahieren:
    - Klicken Sie mit der rechten Maustaste auf die heruntergeladene ZIP-Datei und wählen Sie "Alle extrahieren...", um den Inhalt an einem gewünschten Ort zu entpacken.
3. Zum “PATH” hinzufügen (Optional):
    - Um das Tool von jedem Kommandozeilenfenster aus zugänglich zu machen, fügen Sie das Verzeichnis zum System-“PATH” hinzu:
    - Öffnen Sie die Systemsteuerung > System und Sicherheit > System.
    - Klicken Sie auf Erweiterte Systemeinstellungen > Umgebungsvariablen.
    - Unter Systemvariablen suchen Sie die Variable "Path", wählen diese aus und klicken auf Bearbeiten.
    - Klicken Sie auf Neu und fügen Sie den Pfad zum extrahierten Verzeichnis hinzu.
    - Klicken Sie auf OK, um alle Dialoge zu schließen.
4. Führen Sie das Tool aus:
    - Öffnen Sie ein Command Prompt- oder PowerShell-Fenster.
    - Navigieren Sie zu dem Verzeichnis, in das Sie das Tool extrahiert haben, oder wenn es dem PATH hinzugefügt wurde, geben Sie einfach ein:
```sh
twitch.exe --help
```

## Nutzungsanleitung
### Grundlegende Nutzung
Sobald das Tool installiert ist, können Sie es von einem Terminal aus ausführen. Unten finden Sie einige grundlegende Beispiele für die Nutzung:

#### Grundlegende Utilities:
- --help: Displays the help information.
```sh
twitch.exe --help
```
- --version: Zeigt die Version des Tools an.
```sh
twitch.exe --version
```

#### Unterstützte Befehle:
- view-users: Zeigt eine Liste der aktuell aufgenommenen Benutzer an
 
```shell
twitch.exe view-users
```
- produce-csv: Generiert eine CSV-Datei in Ihrem aktuellen Verzeichnis mit den Twitch-Daten aller aufgenommenen Benutzer
```shell
twitch.exe produce-csv
```
- add-users: Nimmt neue Benutzer in das Tool auf
```shell
twitch.exe add-users -u <username1> <username2> <username3> ...
```
- delete-users: Entfernt Benutzer aus dem Tool
```shell
twitch.exe delete-users -u <username1> <username2> <username3> ...
```
- get-user: Zeigt die Twitch-Daten für einen bestimmten Benutzer an
```shell
twitch.exe get-user -u <username>
```

