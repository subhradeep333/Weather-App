<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Weather App README</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      max-width: 800px;
      margin: auto;
      padding: 20px;
      line-height: 1.6;
      background: #f4f4f4;
    }
    h1, h2 {
      color: #2c3e50;
    }
    code {
      background: #eee;
      padding: 2px 6px;
      border-radius: 4px;
    }
    pre {
      background: #eee;
      padding: 10px;
      border-radius: 4px;
      overflow-x: auto;
    }
    img {
      max-width: 100%;
      border-radius: 10px;
    }
  </style>
</head>
<body>

  <h1>🌦️ Weather App</h1>
  <p>A simple and responsive Weather App that allows users to search for any city and instantly view the current weather conditions including temperature, humidity, and weather description.</p>

  <h2>🔍 Features</h2>
  <ul>
    <li>🌍 Search for any city around the world</li>
    <li>🌤️ Displays real-time weather data</li>
    <li>💧 Shows temperature, humidity, and weather condition</li>
    <li>📱 Fully responsive design – works seamlessly on mobile and desktop</li>
    <li>🎨 Stylish gradient background for an appealing UI</li>
  </ul>

  <h2>🛠️ Built With</h2>
  <ul>
    <li>HTML5</li>
    <li>CSS3 (with gradient styling and responsive layout)</li>
    <li>JavaScript (for API integration and dynamic content)</li>
  </ul>

  <h2>📷 Preview</h2>
  <p><img src="preview.png" alt="Weather App Preview" /></p>
  <p><em>Replace with your own screenshot (name it <code>preview.png</code> and place it in your project folder)</em></p>

  <h2>🚀 How to Use</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/your-username/weather-app.git</code></pre>
    </li>
    <li>Navigate to the project folder:
      <pre><code>cd weather-app</code></pre>
    </li>
    <li>Open <code>index.html</code> in your browser.</li>
  </ol>
  <p><strong>💡 Note:</strong> Make sure you have an active internet connection, as the app fetches weather data from an external API.</p>

  <h2>🔑 API</h2>
  <p>This app uses the <strong>OpenWeatherMap API</strong> for real-time weather data.</p>
  <ol>
    <li>Go to <a href="https://openweathermap.org/api" target="_blank">https://openweathermap.org/api</a></li>
    <li>Sign up and generate a free API key</li>
    <li>Replace the placeholder API key in your JavaScript file:
      <pre><code>const apiKey = "YOUR_API_KEY_HERE";</code></pre>
    </li>
  </ol>

  <h2>📱 Responsiveness</h2>
  <p>The app layout automatically adapts to different screen sizes using flexible width and media queries for an optimal user experience across devices.</p>

  <h2>📂 Folder Structure</h2>
  <pre><code>
weather-app/
│
├── index.html
├── style.css
├── script.js
└── preview.png
  </code></pre>

  <h2>📃 License</h2>
  <p>This project is open-source and free to use for educational or personal purposes.</p>

</body>
</html>
