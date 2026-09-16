# ToDo-Applikation mit Docker

Eine einfache ToDo-Applikation (Node.js), containerisiert mit Docker.

## Installation

### 1. Repository klonen

git clone https://github.com/Saajith582/docker-nodejs-saajith.git
cd docker-nodejs-saajith

### 2. Notwendige Pakete installieren

npm install

### 3. Docker-Konfiguration und -Installation

Docker Desktop muss installiert sein: https://www.docker.com/products/docker-desktop/

Die Docker-Assets (Dockerfile, compose.yaml) wurden mit folgendem Befehl erstellt:

docker init

### 4. Applikation im Docker-Container starten

docker compose up --build

Die Applikation ist danach erreichbar unter:

http://localhost:3000