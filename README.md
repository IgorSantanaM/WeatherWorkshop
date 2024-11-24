# Weather App 🌦️

A simple and responsive web application that displays the current weather of any city using a weather API. This project is built with **React** for the frontend and **Axios** for handling HTTP requests.

---

## Features 🚀

- 🌐 **Search by city**: Enter any city name to fetch real-time weather information.
- 🌞 **Responsive design**: Fully functional across desktops, tablets, and mobile devices.
- 📡 **Real-time data**: Integrates with a weather API to deliver up-to-date weather details.

---

## Tech Stack 🛠️

- **Frontend**: [React](https://reactjs.org/) 
- **HTTP Client**: [Axios](https://axios-http.com/)
- **API**: OpenWeatherMap (or any other weather API of your choice)

---

## Getting Started 🏁

Follow these steps to set up and run the project locally.

### Prerequisites

1. **Node.js**: Install [Node.js](https://nodejs.org/) (LTS version recommended).
2. **API Key**: Sign up for an account with a weather API provider (e.g., [OpenWeatherMap](https://openweathermap.org/)) and get an API key.

---

### Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/weather-app.git
   cd weather-app
   ```

2. Install dependencies:

```bash
npm install
```
3. Create an .env file in the root directory and add your API key:

```env
REACT_APP_WEATHER_API_KEY=your_api_key_here
REACT_APP_WEATHER_API_URL=https://api.openweathermap.org/data/2.5/weather
```
4. Start the development server:

```bash
npm start
```
