🚴‍♂️ Nomad Cyclist

A simple and interactive web application for cyclists to check weather conditions before going for a ride. Built using HTML, CSS, and 
JavaScript, this project uses a Weather API to provide real-time weather updates.

link :- https://anand-chauhan.github.io/nomad_tour/
🌟 Features
🌤️ Check real-time weather conditions
📍 Search weather by city name
🌡️ Displays temperature, humidity, and weather status
🚴 Helps cyclists decide the best time to ride
⚡ Fast and lightweight UI

🛠️ Tech Stack
HTML – Structure of the application
CSS – Styling and layout
JavaScript (ES6) – Logic and API handling
Weather API – Fetch real-time weather data

📂 Project Structure
Nomad-Cyclist/
│
├── index.html
├── style.css
├── script.js
└── README.md

⚙️ How It Works
User enters a city name
JavaScript fetches weather data using fetch() from the Weather API
Weather details are displayed on the screen
Cyclist can decide whether conditions are suitable for riding 🚴‍♂️

🔑 API Integration
Uses a Weather API (like OpenWeatherMap or WeatherAPI)
Fetch request example:

fetch(`https://api.weatherapi.com/v1/current.json?key=YOUR_API_KEY&q=${city}`)
  .then(response => response.json())
  .then(data => {
    console.log(data);
  });
🚀 How to Run the Project

Clone the repository:

git clone https://github.com/your-username/nomad-cyclist.git

Open index.html in your browser
Add your API key in script.js


🎯 Future Improvements
📊 Add hourly and weekly forecast
🗺️ GPS-based location detection

📱 Make it fully responsive

🚴 Add ride suggestions based on weather
