# Interactive Map of Sant Josep

This project is an **interactive web map application** that allows users to explore various points of interest in Sant Josep de sa Talaia. It is built with **Leaflet.js** and uses JSON data to display information across different categories, including beaches, churches, museums, towers, and libraries.

## Features

### Interactive Map
- Displays points of interest with markers on the map.
- Each marker shows a **popup** with detailed information: image, name, description, and a link to the website (if available).
- Marker icons are differentiated by category.

### Category Filter
- Select a category from the dropdown to show only points belonging to that category.
- Filtered results are also displayed in a sidebar with interactive cards.

### Search by Name
- A search field allows filtering results based on user input.
- Matches are insensitive to accents and spaces (for example, "cala bassa" and "calabassa" are treated as equal).

### Geolocation
- Button to locate the user on the map and center the view on their current position.

### Responsive Design
- On mobile devices, filter results and the map can be toggled using buttons.
- On desktop, the map and filter panel are displayed simultaneously.
- Marker icons and zoom levels adjust automatically based on screen size.

### Result Interaction
- Clicking a result card centers the map on the corresponding marker and opens its popup.

## Project Structure

- `index.html` → Contains the main structure for the map and filter panel.
- `style.css` → Custom styles for the map, filters, and result cards.
- `mapdata.js` → JSON file containing information about the points of interest.
- `Leaflet.js` and `Leaflet.css` → Library for interactive maps.
