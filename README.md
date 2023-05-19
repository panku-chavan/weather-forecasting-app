![Application screenshot](./public/screenshot.png)

<br/>

[The Weather Forecasting](https://the-weather-forecasting.netlify.app) app is developed using React.js and material-UI. User can search locations by city name and observe the weather for the next 5-6 days and 3 hour interval.

# Live Demo:

Link: https://the-weather-forecasting.netlify.app

# Getting Started

- Make sure you already have `Node.js` and `npm` installed in your system.
- You need an API key from [OpenWeatherMap](https://openweathermap.org/). After creating an account, [grab your key](https://home.openweathermap.org/api_keys).
- Then, under the `src` directory, go to `api/OpenWeatherService` and replace `WEATHER_API_KEY` with your OpenWeatherMap API Key.
  - **`api/OpenWeatherService.js`**: It contains the code related to the back-end of the application.

# Install

- Clone the repository:

```bash
git clone https://github.com/Amin-Awinti/the-weather-forecasting.git

```

- Install the packages using the command `npm install`

# Used libraries

- `react-js`
- `material-ui`

Check `packages.json` for details

## Todos

- [ ] Styled-components
- [ ] Convert the entire project to TypeScript
- [ ] Unit Testing
- [ ] On launch, find user location weather by utilizing GeolocationAPI/GEOCODING
- [ ] Celcius/Fahrenheit conversion
- [ ] Dark/Light Mode

<br/>
Thank You ^\_^
