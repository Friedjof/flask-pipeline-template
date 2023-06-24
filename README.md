# Flask Template Projekt
## Dokumentation
Bei jedem push in den `master` Branch und Änderungen an nicht `.md` Dateien wird automatisch
eine neue Version auf dem Server deployt.

## Lokale Entwicklung
### Installation
1. Installiere Docker, Python und Pip
2. Installiere die Python Abhängigkeiten mit `pip install -r requirements.txt`
3. Starte die Anwendung mit `python app.py`

### Docker
1. Starte die Anwendung mit `docker-compose up -d` (startet die Anwendung und eine Datenbank)
2. Öffne die Anwendung im Browser unter `http://0.0.0.0/`

## Server
### Installation
1. Installiere Docker
2. Installiere und starte den Github Runner (siehe die [Dokumentation](https://docs.github.com/en/actions/hosting-your-own-runners/adding-self-hosted-runners))
