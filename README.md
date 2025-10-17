# Weather Dashboard

Welcome to the Weather Dashboard project! This application allows users to enter a city name and view the current weather details using the OpenWeather API. The displayed data includes temperature, humidity, and weather icons for a clear and quick overview of the weather conditions in a specific location.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [File Structure](#file-structure)
- [API Reference](#api-reference)
- [Contributing](#contributing)
- [License](#license)

## Features

- User-friendly interface for entering a city name.
- Retrieves and displays current weather information:
  - Temperature
  - Humidity
  - Weather icons depicting current conditions
- Powered by the reliable OpenWeather API.

## Installation

To run this project locally, follow these steps:

1. Clone this repository to your local machine using:

   ```bash
   git clone https://github.com/yourusername/weather-dashboard.git
   ```

2. Navigate into the project directory:

   ```bash
   cd weather-dashboard
   ```

3. Open the `index.html` file in your preferred web browser to run the application.

## Usage

1. Open the `index.html` file in a web browser.
2. Enter the name of a city in the input field.
3. Upon submission, view the current temperature, humidity, and a weather icon representing the current weather conditions for the specified city.

## File Structure

- `index.html`: This is the main HTML file for the project. It contains the structure and layout for the weather dashboard application.

## API Reference

This project uses the [OpenWeather API](https://openweathermap.org/api) to fetch weather data.

### Getting an API Key

To use the OpenWeather API, you need an API key. Follow these steps:

1. Sign up at [OpenWeather](https://openweathermap.org/).
2. Generate an API key from your account dashboard.
3. Use this API key within your application to fetch weather data.

### API Usage

Ensure to replace `{API_KEY}` with your OpenWeather API key in the API call within the application.

Example API call structure:

```
https://api.openweathermap.org/data/2.5/weather?q={city name}&appid={API_KEY}
```

## Contributing

We welcome contributions to enhance the Weather Dashboard! Please fork the repository and submit a pull request for any improvements or additions you wish to make.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the LICENSE file for details.

---

Enjoy using the Weather Dashboard? Feel free to share your feedback and suggestions for improvement. Happy weather tracking!