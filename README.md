# 🌤️ Umbrelino – Your Meteorolog

This project implements **Umbrelino**, an intelligent AI Weather Agent that delivers **cheerful, funny, and uplifting daily weather updates** via email.  
Umbrelino fetches real-time weather data for the user’s location and sends a positive morning message every day at 7:00 AM local time.

---

## ✨ Features

- 🌍 **Fetch geolocation** using the location provided (`{{Location}}`).  
- ☀️ **Retrieve weather forecast** from APIs such as OpenWeatherMap or WeatherAPI:  
  - Temperature (min/max)  
  - Weather description (sunny, rainy, etc.)  
  - Wind and special alerts (heatwave, snowstorm, etc.)  
- 😄 **Generate humorous and uplifting messages** based on the forecast:  
  - Friendly, funny, and natural language tone  
  - Positive and personalized for the user  
  - Includes one emoji for extra vibe  
- 📧 **Send daily emails** to recipients (`{{Recipients}}`) using the Email Sender tool.  
- ⏰ **Automatic scheduling**: ensures delivery every morning at 7:00 AM in the local timezone.  
- 💡 **Fallback logic**: if location or weather data is unavailable, sends a motivational message instead:  
---

## 📖 Example Email:
🌞 Good morning, Mihai!

Today in Bucharest, the sun is shining brighter than your morning coffee! Expect a toasty high of 27°C and a comfy low of 17°C. Perfect weather to strut your stuff and soak up some Vitamin D!

Pro tip: Don’t forget your shades—the UV index is working overtime today. And hey, the sky’s so clear, it might just be jealous of your weekend plans.

No rain, no pain—just sunshine and smiles all day. Go out and make it awesome!

Cheers to a sunny day! 🌟

## 💡 Skills & Technologies Learned

- **RPA / UiPath Studio Web workflows**  
- **AI Agent Design** for natural language generation  
- **API integration** (OpenWeatherMap, WeatherAPI)  
- **Email automation** with dynamic templates  
- **Scheduling and time zone handling**  
- **Humor and sentiment-aware messaging**

- ---

> "Brighten someone's morning—one weather report at a time!" 🌟
