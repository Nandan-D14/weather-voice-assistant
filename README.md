
# 🌦️ Weather App with Voice Assistant

### 👨‍🎓 First Year Group Project  
**Team Members**: Nandan D & Tarun  
**Built Using**: Python, Tkinter, APIs, and AI modules

---

## 📌 Project Overview

This is a **GUI-based Weather Application** with **speech recognition** and **air quality tracking**. Built using Python and Tkinter, the app can fetch and speak out weather reports based on user input (both text and voice).

It uses:
- **OpenWeatherMap API** for real-time weather and air quality
- **Geopy + TimezoneFinder** for geolocation and timezone
- **SpeechRecognition** for voice input
- **pyttsx3** for text-to-speech feedback

---

## ✨ Features

- 📍 Get **current location weather** by entering a city name
- 🎤 **Voice-enabled search** (Google Speech Recognition)
- 🔊 Weather report spoken aloud using **text-to-speech**
- 📅 **7-day forecast preview** with icons and temperatures
- 🧭 Show **timezone and coordinates** for searched cities
- 💨 Live **air quality index (AQI), PM2.5, PM10 levels**
- 🎨 **Changeable theme/background color**
- 🧭 Real-time **clock and location details**
- 🧪 Lightweight GUI with image previews and animations

---

## 🖥️ Technologies Used

| Module             | Purpose                                  |
|--------------------|------------------------------------------|
| `tkinter`          | GUI Design                               |
| `requests`         | API Handling                             |
| `PIL`              | Image Rendering                          |
| `geopy`            | City -> Coordinates Conversion            |
| `timezonefinder`   | Determine timezone of location           |
| `speech_recognition` | Capture voice and convert to text       |
| `pyttsx3`          | Voice assistant (text-to-speech)         |
| `colorchooser`     | Change background color dynamically      |
| `OpenWeatherMap API` | Weather and Air Quality data           |

---

## 🔧 How to Run

### 1. 🔗 Install Required Libraries:
```bash
pip install requests
pip install geopy
pip install timezonefinder
pip install pyttsx3
pip install SpeechRecognition
pip install pillow
pip install colorama
````

### 2. 📦 Get Your Own OpenWeatherMap API Key

Register at [https://openweathermap.org/](https://openweathermap.org/) and generate an API key. Replace it inside the script where noted.

### 3. 🖼️ Add Necessary Images

Put weather icons (e.g. `01d.png`, `02n.png` etc.) and GUI assets like:

* `mick_image.png`
* `Rounded Rectangle 1.png`
* `Rounded Rectangle 2.png`
* `Rounded Rectangle 2 copy.png`
* `Rounded Rectangle 3.png`
* `Layer 6.png`
* `Layer 7.png`

Inside `mini_pro_img/` or respective folder paths.

### 4. ▶️ Run the App:

```bash
python weather_app.py
```

---

## 📸 Screenshots

> *Include some GUI screenshots of your app here for better presentation.*

---

## 📚 Credits

This project was developed by **Nandan D** and **Tarun** as part of our **first-year group project** at \[Your Institution Name].

---

## 📌 Note

* Some paths like `"C:\\Users\\Nandan\\Downloads\\mini_pro_img\\..."` need to be changed based on your file system.
* Make sure your **microphone is working** for voice input.
* Internet connection is required to fetch live weather data.

---

## 📄 License

This project is for educational purposes only.

```

---

Let me know if you want this in `.md` file format to upload directly, or want to split version 1 and 2 in folders for GitHub.
```
