# 🌤️ Async Weather Tracker

A simple **JavaScript weather application** that demonstrates **asynchronous programming, API integration, and the JavaScript event loop**.
Users can search for any city to get real-time weather data and view how async operations execute through a built-in console log.

---

## 📌 Features

* 🔎 Search weather by **city name**
* 🌡 Displays **temperature, humidity, wind speed, and weather condition**
* 🕘 **Search history** saved using Local Storage
* ⚡ Demonstrates **JavaScript Event Loop behavior**

  * Synchronous execution
  * Microtasks (`Promise.then`)
  * Macrotasks (`setTimeout`)
* 🧾 Built-in **console panel** to visualize async execution
* 🎨 Clean **weather-themed UI**

---

## 🛠️ Technologies Used

* **HTML5**
* **CSS3**
* **JavaScript (ES6+)**
* **OpenWeatherMap API**
* **Local Storage API**

---

## ⚙️ How It Works

1. The user enters a city name.
2. The app triggers the `executeWeatherSearch()` function.
3. This function logs:

   * synchronous operations
   * microtasks (`Promise.then`)
   * macrotasks (`setTimeout`)
4. The app fetches weather data asynchronously using `fetch()` from the **OpenWeatherMap API**.
5. Weather data is displayed in the UI.
6. The searched city is stored in **Local Storage** for quick access later.

---

## 📂 Project Structure

```
Async-Weather-Tracker
│
├── index.html       # Main project file (HTML, CSS, JS)
└── README.md        # Project documentation
```

---

## 🌐 API Used

Weather data is provided by:

**OpenWeatherMap API**

API Endpoint used:

```
https://api.openweathermap.org/data/2.5/weather
```

Example request:

```
https://api.openweathermap.org/data/2.5/weather?q=London&appid=YOUR_API_KEY&units=metric
```

---

## ▶️ How to Run the Project

1. Download or clone the repository.

```
git clone https://github.com/yourusername/async-weather-tracker.git
```

2. Open the project folder.

3. Open **index.html** in any web browser.

4. Enter a city name and click **Search**.

---

## 📸 Example Output

The app displays:

* City Name
* Temperature (°C)
* Weather Condition
* Humidity
* Wind Speed

It also logs async behavior inside the **Console - Event Loop panel**.

---

## 🎯 Learning Objectives

This project helps understand:

* Asynchronous JavaScript
* `async / await`
* API requests using `fetch`
* JavaScript Event Loop
* Microtasks vs Macrotasks
* Local Storage
* Basic UI design with CSS

---

## 🚀 Future Improvements

* Add **weather icons**
* Add **5-day weather forecast**
* Add **geolocation weather detection**
* Add **dark/light theme toggle**
* Deploy using **GitHub Pages**

---

## 👨‍💻 Author

**Divyant Podder**

Computer Science Engineering Student
Interested in **Cybersecurity, Blockchain, and Web Development**

---

⭐ If you like this project, consider giving it a **star on GitHub**.
