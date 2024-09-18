# To-Do Applikation

## Installation des Projekts

- **Klonen des Repositories**
  - Auf Github im Repositorie, das du klonen willst auf die Schaltfläche **"Fork"** klicken.
  - `git clone git@github.com:AlexaLovegood/docker-nodejs-sample-todo-list.git` um es auf den Rechner zu klonen
- **Installation der notwendigen Pakete**
  - Windows Subsystem for Linux installieren (WSL)
- **Docker-Konfiguration und -Installation**
  - Docker Desktop & Docker for VS Code installieren
  - Im Projektordner über die Eingabeaufforderung mit `Docker Init` aktivieren
    - What application platform does your project use? = **Node**
    - What version of Node do you want to use? = **18.0.0**
    - Which package manager do you want to use? = **npm**
    - What command do you want to use to start the app: = **node src/index.js**
    - What port does your server listen on? = **3000**
- **Starten der Applikation in einem Docker-Container**
  - Du baust sie mit `docker compose up --build` sie startet dabei automatisch
