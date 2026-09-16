# Projekt-Dokumentation & Installationsanleitung

Diese Dokumentation bietet eine ausführliche, schrittweise Anleitung zur Einrichtung, Konfiguration und zum Starten der Node.js-Anwendung mithilfe von Docker sowie zur Nutzung in Visual Studio Code.

---

## 1. Einbindung in Visual Studio Code (Anleitung)

1. Öffne den geklonten Projektordner in **VS Code** (`Datei` -> `Ordner öffnen...`).
2. Erstelle im Hauptverzeichnis des Projekts eine neue Datei namens `README.md`.
3. Kopiere diesen gesamten Inhalt in die Datei und speichere sie (`Strg + S` bzw. `Cmd + S`).
4. **Tipp:** Drücke `Strg + K, V` (oder klicke oben rechts auf das Vorschau-Symbol), um das Dokument formatiert anzuzeigen.

---

## 2. Prerequisites (Voraussetzungen)

Bevor du mit der Installation beginnst, stelle sicher, dass folgende Software auf deinem System installiert ist und ordnungsgemäß funktioniert:

1. **Git**: Zum Klonen des Quellcodes ([Git Herunterladen](https://git-scm.com/)).
2. **Node.js & npm**: Zur Verwaltung der JavaScript-Pakete ([Node.js Herunterladen](https://nodejs.org/)).
3. **Docker Desktop**: Zur Ausführung der Anwendung in Containern ([Docker Desktop Herunterladen](https://www.docker.com/products/docker-desktop/)).
   > **Wichtig:** Docker Desktop muss während der gesamten Ausführung gestartet sein und im Hintergrund laufen.

---

## 3. Schritt-für-Schritt-Installation

### Schritt 1: Repository klonen (Quellcode herunterladen)

Öffne das Terminal in VS Code (`Terminal` -> `Neues Terminal`) und führe folgende Befehle aus:

```bash
# 1. Klonen des Repositories von GitHub auf deinen lokalen Rechner
git clone [https://github.com/Saajith582/docker-nodejs-saajith.git](https://github.com/Saajith582/docker-nodejs-saajith.git)

# 2. Wechseln in das neu erstellte Projektverzeichnis
cd docker-nodejs-saajith