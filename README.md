# Weather App ☁️🌡️

## Overview

This Weather App is built using Vite and React.js, integrating with the OpenWeatherMap API. The application allows users to search for a city and displays the current climate, humidity, wind speed, and temperature of the specified location.

## Features

- **Search Functionality**: Enter the name of a city to get the current weather information.
- **Weather Details**: Displays climate, humidity, wind speed, and temperature.
- **Responsive Design**: Works well on both desktop and mobile devices.

## Installation

Follow these steps to set up and run the project locally:

### Prerequisites

- Node.js (v14 or higher recommended)
- npm (v6 or higher recommended) or yarn

### Steps

1. **Clone the Repository**

   ```bash
   git clone https://github.com/Tharunmoonwalker/weather-reactjs.git
   cd weather-app
   ```

2. **Install Dependencies**

   Using npm:
   ```bash
   npm install
   ```

   Using yarn:
   ```bash
   yarn install
   ```

3. **Set Up Environment Variables**

   Create a `.env` file in the root directory and add your OpenWeatherMap API key:

   ```plaintext
   VITE_APP_ID=your_openweather_api_key
   ```

4. **Run the Development Server**

   Using npm:
   ```bash
   npm run dev
   ```

   Using yarn:
   ```bash
   yarn dev
   ```

5. **Open the App**

   Open your browser and navigate to `http://localhost:5173/` to see the application in action.

## Usage

1. **Search for a City**: Enter the name of a city in the search bar and press enter.
2. **View Weather Information**: The app will display the current climate, humidity, wind speed, and temperature for the specified city.

## Technologies Used

- **Vite**: For fast and optimized build.
- **React.js**: For building the user interface.
- **OpenWeatherMap API**: For fetching weather data.

## Project Structure

```plaintext
weather-app/
├── public/
│   └── index.html
├── src/
│   ├── components/
│   │   └── Weather.jsx
│   ├── App.jsx
│   ├── main.jsx
│   └── styles/
│       └── App.css
├── .env
├── .gitignore
├── package.json
├── README.md
└── vite.config.js
```

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please create an issue or submit a pull request.

1. Fork the repository.
2. Create your feature branch: `git checkout -b feature/your-feature-name`.
3. Commit your changes: `git commit -m 'Add some feature'`.
4. Push to the branch: `git push origin feature/your-feature-name`.
5. Open a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Acknowledgements

- [OpenWeather API](https://openweathermap.org/api) for providing the weather data.

---
Feel free to clone folks ! Have a Marvellous day
 
