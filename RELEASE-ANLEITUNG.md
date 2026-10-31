# Release v1.1.0 fertigstellen

Die Release-Version ist auf GitHub als Entwurf angelegt. Hänge vor dem Veröffentlichen beide Dateien an:

1. Öffne **Releases** im Repository und bearbeite den Entwurf **LinguaLoop 1.1.0**.
2. Lade aus dem lokalen Ordner `release-assets` diese beiden Dateien hoch:
   - `LinguaLoop-Setup-v1.1.0.exe`
   - `LinguaLoop-v1.1.0-win-x64.zip`
3. Prüfe, dass beide Dateien unter **Assets** stehen.
4. Klicke **Publish release**.

Der Installer ist für neue Nutzer. Das ZIP lädt der automatische Updater bei späteren Versionen herunter. Beide Dateien sind zusammen etwa 238 MB groß. Der Quellcode wird nicht im Release-Repository abgelegt.

## Fertige lokale Dateien

Im Ordner `release-assets` liegen beide Dateien. Der Ordner ist mit Absicht in `.gitignore` ausgeschlossen; GitHub Releases verwaltet große Binärdateien als Assets statt im normalen Git-Verlauf.
