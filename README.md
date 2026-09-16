# Node.js App mit Docker

Anleitung zur Installation und Ausführung des Projekts

---

## Installation des Projekts

### 1. Klonen des Repositories
Lade den Quellcode von GitHub auf deinen Computer herunter und wechsle in den Projektordner.

### 2. Installation der notwendigen Pakete
Installiere alle benötigten Node.js-Abhängigkeiten für das Projekt.

### 3. Docker-Konfiguration und -Installation
Stelle sicher, dass **Docker Desktop** auf deinem Rechner installiert ist und läuft. Die Konfigurationsdateien (`Dockerfile` und `compose.yaml`) sind bereits im Projekt enthalten.

### 4. Starten der Applikation in einem Docker-Container
Starte den Docker-Container und öffne die Anwendung im Browser unter `http://localhost:3000`.

---

## Alle Befehle auf einen Blick

Kopiere diese Befehle und führe sie nacheinander im VS Code Terminal (`Strg + J` oder `Terminal -> Neues Terminal`) aus:

```bash
git clone [https://github.com/Saajith582/docker-nodejs-saajith.git](https://github.com/Saajith582/docker-nodejs-saajith.git)
cd docker-nodejs-saajith
npm install
docker compose up --build