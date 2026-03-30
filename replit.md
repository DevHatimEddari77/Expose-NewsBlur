# Exposé NewsBlur

## Overview
A static HTML presentation about NewsBlur — a news aggregation platform. The slide deck supports Arabic and French, with interactive navigation and language switching.

## Project Structure
- `expose_newsblur.html` — The main (and only) HTML file containing the full presentation
- `server.py` — A minimal Python HTTP server that serves the HTML file on port 5000

## Running the App
The app is served via a Python `http.server` on port 5000. The workflow "Start application" runs `python server.py`.

## Deployment
Configured as a static site deployment with the project root as the public directory.
