# Monument Navigation Map (c178)

A Mapbox GL web page that places image markers on a map for famous Indian monuments (Amber Fort, Gateway of India, India Gate, Lotus Temple, Victoria Memorial).

## Features
- Mapbox GL map centered on Kolkata with zoom controls
- Mapbox Geocoder search plugin
- Custom image markers (photos) for 5 monuments using coordinates

## Tech Stack
- HTML / CSS / JavaScript
- Mapbox GL JS v2.1.1
- Mapbox GL Geocoder
- jQuery, Bootstrap 4

## Project Structure
```
c178/
├── main.html      # page markup
├── main.js        # Mapbox map + markers
├── main.css
└── assets/        # monument images (jpg)
```

## Installation
No dependencies to install — Mapbox, jQuery and Bootstrap load from CDNs.

## Usage
Serve the folder over HTTP and open `main.html`:
```bash
python3 -m http.server 8000
```
The map loads, centered on the initial coordinates, with the monument image markers placed at their real-world landmarks.