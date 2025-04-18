# Weather App 🌦️

A simple weather application built with **React** and **Vite**, utilizing the **OpenWeather API** to fetch current weather and forecasts.

## Features ✨
- 🌍 Search weather by city name
- 📊 Display current weather conditions
- 🔮 5-day weather forecast
- 🔥 Temperature gauge visualization
- 🌗 Light/Dark mode support
- 🕰️ Search history stored in local storage
- 🔎 City name suggestions

## Technologies Used 🛠️
- **React** (Functional Components, Hooks)
- **Vite** (Fast development environment)
- **Tailwind CSS** (For styling)
- **Axios** (For API requests)
- **OpenWeather API** (Weather data provider)

## Installation ⚙️

### Prerequisites
- Node.js installed

### Steps
1. Clone this repository:
   ```sh
   git clone https://github.com/your-username/weather-app.git
   cd weather-app
   ```
2. Install dependencies:
   ```sh
   npm install
   ```
3. Create a `.env` file in the project root and add your **OpenWeather API key**:
   ```sh
   VITE_API_KEY=your_api_key_here
   ```
4. Start the development server:
   ```sh
   npm run dev
   ```
5. Open the app in your browser at `http://localhost:5173`

## Usage 📖
- Type a city name in the search bar.
- Select a suggestion or press enter to fetch the weather.
- View the temperature gauge and weather details.
- Toggle between light and dark mode.
- Check recent search history.

## Environment Variables 🌍
Ensure you add the **API key** in your `.env` file:
```
VITE_API_KEY=your_api_key_here
```

## Folder Structure 📂
```
/weather-app
│── src
│   ├── components (UI Components)
│   ├── context (API Context)
│   ├── pages (Main Pages)
│   ├── App.jsx (Main App File)
│   ├── main.jsx (Entry Point)
│── .env (API Key - Not committed)
│── package.json
│── README.md
```

## Deployment 🚀
To deploy, build the project:
```sh
npm run build
```
Then, deploy using **Vercel**, **Netlify**, or **GitHub Pages**.

## License 📜
This project is **open-source** under the MIT License.

## Contributions 🤝
Pull requests and suggestions are welcome! Feel free to fork and improve.

---
💙 Built with love using React & Vite! 🌍

