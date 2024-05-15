# bike_stations.html
# Citi Bike Map Visualization

This repository contains code to create an interactive map that visualizes Citi Bike station locations and details in New York City using Leaflet.js and D3.js. The map displays bike stations, their locations, and capacities using markers and popups.

### Table of Contents

- Installation
- Usage
- Example

# Installation

1. Clone the repository:
git clone https://github.com/Bnrobertson/bike_stations.git
2. Navigate to the repository directory:
cd bike_stations
3. Ensure you have a local server to serve the HTML file, as some browser security settings may prevent local AJAX calls. You can use a simple HTTP server with Python:
python -m http.server

# Usage

1. Open the index.html file in a web browser. If using a local server, navigate to http://localhost:8000/index.html.

2. The map will load and display bike stations with markers. Each marker can be clicked to display a popup with the station name and capacity.

Example

- JavaScript
The core functionality is implemented in the static/js/logic.js file:
- HTML
The HTML structure is in the index.html file:
- CSS
The CSS styling is in the static/css/style.css file:
