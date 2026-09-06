# CloudCast

CloudCast is a lightweight weather dashboard for checking current conditions and a seven-day forecast by city. It uses a responsive glass-style interface and runs entirely in the browser with no build step or API key required.

## Features

- Search for weather by city name
- View current temperature, feels-like temperature, humidity, wind speed, and conditions
- See a seven-day high and low forecast
- Compare current temperatures in a few major cities
- Use the search button or press `Enter`
- Get clear loading and error states when a request cannot be completed
- Responsive layout for desktop and mobile screens

## Built With

- HTML5
- CSS3, including custom properties, gradients, and responsive media queries
- Vanilla JavaScript (ES6+)
- [Open-Meteo Geocoding API](https://open-meteo.com/en/docs/geocoding-api)
- [Open-Meteo Forecast API](https://open-meteo.com/en/docs)

## Getting Started

### Run locally

1. Clone or download this repository.
2. Open `weather.html` in a modern web browser.
3. Search for a city to load its weather data.

No installation, build command, or API key is required. Because the app requests live data from Open-Meteo, an internet connection is needed for searches.

### Optional local server

For a local development server, run the following from the project directory:

```bash
python -m http.server 8000
```

Then open <http://localhost:8000/weather.html>.

## Project Structure

```text
.
├── weather.html   # Application markup, styles, and JavaScript
├── style.css      # Additional stylesheet for the original layout
└── README.md      # Project documentation
```

## Browser Support

CloudCast requires a modern browser with support for:

- ES6+ JavaScript
- The Fetch API
- CSS custom properties
- `backdrop-filter`

## Data and Attribution

Weather and geocoding data are provided by [Open-Meteo](https://open-meteo.com/). Forecast data is subject to the availability and accuracy of the upstream service.

## License

This project is provided for educational and personal use.
