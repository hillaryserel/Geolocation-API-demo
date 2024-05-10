# Geolocation API Demo

This project demonstrates the use of the Geolocation API to find the user's current location and display it on a Google Map.

## Features

- **Find Location Button**: When clicked, the application uses the Geolocation API to get the user's current location.
- **HTTPS Check**: The application checks if the page is accessed over HTTPS. If not, it either reloads the page over HTTPS or displays a message.
- **Geolocation API Support Check**: The application checks if the browser supports the Geolocation API. If not, it displays a message.
- **Display Coordinates**: The application displays the latitude and longitude of the user's location.
- **Google Map**: The application creates a Google Map and places a marker at the user's location. The map is re-centered on the user's location when the window/viewport resizes.

## Usage

1. Open the HTML file in a browser.
2. Click the "Find your location" button.
3. Allow the browser to access your location.

## Note

Most browsers require HTTPS to run the Geolocation API.

## Dependencies

- jQuery
- Google Maps JavaScript API
