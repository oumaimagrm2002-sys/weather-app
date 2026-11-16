# MeteoGlass App

MeteoGlass is a modern weather application built with Vue 3 and Vite. It lets users search for a city and instantly view the current weather, hourly temperature trends, and a 5-day forecast in a clean, glassmorphism-inspired interface.

This project is designed for GitHub sharing and can be easily run locally or deployed as a lightweight frontend app.

## Overview

The app fetches live weather data from the OpenWeatherMap API and displays:

- Current temperature and weather condition
- Humidity, wind speed, feels-like temperature, and pressure
- Hourly forecast for the next several hours
- 5-day forecast summary
- Dynamic background images based on the weather condition
- Interactive chart visualization for hourly temperature trends

## Features

- Search weather by city name
- Real-time API-based conditions
- Responsive layout for desktop and mobile
- Modern glass-style design
- Weather-specific visual theme switching
- Simple and fast Vue frontend

## Tech Stack

- Vue 3
- Vite
- Chart.js
- OpenWeatherMap API

## Project Structure

```bash
weather-app/
├── public/
│   ├── images/
│   └── favicon.svg
├── src/
│   ├── App.vue
│   ├── main.js
│   └── style.css
├── index.html
├── package.json
├── README.md
└── vite.config.js
```

## Getting Started

### Prerequisites

Make sure you have the following installed:

- Node.js (v18 or newer recommended)
- npm

### Installation

1. Clone the repository:

```bash
git clone https://github.com/your-username/weather-app.git
cd weather-app
```

2. Install dependencies:

```bash
npm install
```

### Run the app locally

```bash
npm run dev
```

Then open the local address shown in the terminal, typically:

```bash
http://localhost:5173
```

## API Configuration

This app uses the OpenWeatherMap API. In the current project, the API key is stored directly in the Vue component file (`src/App.vue`).

If you want to use your own API key:

1. Sign up at OpenWeatherMap
2. Generate an API key
3. Replace the existing key in `src/App.vue`

Example:

```js
const apiKey = 'YOUR_API_KEY_HERE'
```

Important: for production use, it is recommended to store the key in an environment variable instead of hardcoding it in the frontend.

## Build for Production

```bash
npm run build
```

The production files will be generated in the `dist/` folder.

## Deployment

You can deploy this app on services such as:

- Netlify
- Vercel
- GitHub Pages
- Firebase Hosting

Because it is a Vite app, deployment is straightforward after running the build command.

## Notes

This project is a beginner-friendly weather web app that demonstrates how to connect a Vue frontend to a real API and present the data in a visually appealing interface.

It is an excellent project for learning:

- Vue component structure
- Fetching data from an API
- State management with refs
- Dynamic UI updates
- Integrating chart libraries

## License

This project is open for learning and personal use. If you plan to publish it publicly, consider adding a license file such as MIT.

## Example Screenshot

You can add a screenshot of the app to make the GitHub repository more attractive:

```bash
# Example
# Place your image in the repository and reference it here
# ![MeteoGlass App](./public/images/screenshot.png)
```

## Author

Created as a Vue-based weather dashboard project for learning and portfolio use.
