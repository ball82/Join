# Join – Kanban Task Management

**[Live-Demo](https://www.bajo-dev.ch/sub/join/)**

Webbasiertes Task-Management-Tool mit Kanban-Board, Kontaktverwaltung und Dashboard. Teamprojekt im Rahmen der Developer Akademie.

## Features

- Kanban-Board mit Drag & Drop über vier Spalten (To do, In progress, Await feedback, Done)
- Aufgaben mit Titel, Beschreibung, Fälligkeitsdatum, Priorität und zugewiesenen Kontakten
- Subtasks zum Aufteilen von Aufgaben
- Echtzeit-Suche über alle Aufgaben
- Kontaktverwaltung (anlegen, bearbeiten, löschen)
- Dashboard mit KPI-Karten und nächster Deadline
- Login und Registrierung inkl. Gast-Login
- Responsives Layout (Mobile bis Desktop)

## Technologien

- HTML5
- CSS3
- Vanilla JavaScript (ES6+, modular)
- Firebase Realtime Database
- Firebase Authentication

## Projektstruktur

```
Join/
├── index.html          # Login / Registrierung
├── summary.html        # Dashboard
├── board.html          # Kanban-Board
├── add_task.html       # Aufgabe erstellen
├── contacts.html       # Kontaktverwaltung
├── css/                # Stylesheets
├── scripts/            # JavaScript-Module (Board, Kontakte, Firebase ...)
├── templates/          # Wiederverwendbare HTML-Bausteine
└── img/
```

## Lokaler Start

Die App nutzt Firebase und lädt Ressourcen über relative Pfade, daher wird ein lokaler Webserver empfohlen:

```
npx serve .
```

Anschließend die angezeigte URL im Browser öffnen. Zum Ausprobieren ohne eigenes Konto steht **"Guest Log in"** zur Verfügung.

## Autoren

Teamprojekt im Rahmen der Developer Akademie:

- Joannis Ballos
- Raphael Neuberger
