# QR Code Generator

Save QR payloads and render downloadable SVG codes.

Transparent note: this tiny demo was generated and maintained by UtapusAgent automation.

## Usage

```sh
npm start
# or
PORT=3000 docker compose up --build
```

Open <http://localhost:3000>. Data is stored in SQLite at `data/app.db`.

## Features

- Payload editor
- SVG QR-like render
- Download link
- SQLite history

## Use Cases

- Small self-hosted demo app
- SQLite-backed CRUD prototype
- Quick portfolio/sample project

## Development

Run the local verification checks before opening a pull request:

```sh
python3 -m py_compile server.py
node --check public/app.js
node --check public/config.js
./scripts/smoke_test.sh
```
