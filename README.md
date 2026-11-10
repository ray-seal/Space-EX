# SPACE EX

An interactive, mobile-friendly field guide to the cosmos.

## Explore
- Interactive Solar System and searchable catalogue of planets, moons, stars and extreme objects
- Cosmic oddities, quick knowledge quiz, space mission gallery and scale explorer
- **Sky Now:** browser geolocation, calculated horizon chart, bright stars, constellation stick figures and current planet positions
- **Satellite Watch:** estimated passes for the ISS and selected bright satellites using current CelesTrak orbital elements
- **Sky Calendar:** upcoming meteor showers, planetary pairings, lunar highlights and seasonal events

## Location privacy
The browser asks for location permission only after the visitor taps the location button. Coordinates are kept in page memory and used locally for sky calculations and satellite pass calculations. They are not sent to SPACE EX servers. Satellite orbital data is fetched from CelesTrak and cached in the browser for two hours. Compass access is separately opt-in and device support varies.

## Satellite data
CelesTrak GP OMM JSON data and satellite.js SGP4 propagation are used for satellite pass estimates. These are geometric pass predictions, not guarantees of naked-eye visibility. Sun illumination, brightness, weather, horizon obstructions and light pollution matter. Starlink train predictions link to Find Starlink.

## Stack
Static HTML, CSS and vanilla JavaScript, Astronomy Engine for celestial positions, and satellite.js for orbital propagation. No database, API keys or paid services required.

Astronomical event dates are curated from NASA/JPL skywatching resources. Visibility varies by location and conditions. Facts and discovery counts can change as research advances.
