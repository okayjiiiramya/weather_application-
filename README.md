# 🌦️ Weather Application

A simple and responsive **Weather Application** built using **HTML, CSS, and JavaScript** that provides real-time weather information for different cities using a weather API.

---

## 🚀 Features

- 🌍 Search weather by city name
- 🌡️ Displays current temperature
- ☁️ Shows weather conditions
- 💨 Wind speed information
- 💧 Humidity details
- 📱 Fully responsive design
- ⚡ Fast and lightweight interface

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- OpenWeatherMap API

---

## 📂 Project Structure

```bash
weather_application/
│── assets/
│── index.html
│── style.css
│── script.js
│── README.md
```


## ⚙️ Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/okayjiiiramya/weather_application.git
```

### 2️⃣ Navigate to the Project Folder

```bash
cd weather_application
```

### 3️⃣ Open in Browser

Open `index.html` in your browser.

---

## 🔑 API Setup

1. Go to [OpenWeatherMap](https://openweathermap.org/api)
2. Create a free account
3. Generate your API key
4. Replace the API key inside `script.js`

```javascript
const apiKey = "YOUR_API_KEY";
```

---

## 💻 Example JavaScript Fetch

```javascript
const apiKey = "YOUR_API_KEY";

async function getWeather(city) {
    const apiURL = `https://api.openweathermap.org/data/2.5/weather?q=${city}&units=metric&appid=${apiKey}`;

    const response = await fetch(apiURL);
    const data = await response.json();

    console.log(data);
}
```

---

## 📱 Responsive Design

The application works perfectly on:

- 💻 Desktop
- 📱 Tablet
- 📲 Mobile

---

## ✨ Future Enhancements

- 📍 Current location weather
- 🌙 Dark mode
- 📅 5-day forecast
- 🌡️ Celsius/Fahrenheit conversion
- 🎨 Better animations

---


## 📄 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

Developed with ❤️ by **Ramya Gupta**
