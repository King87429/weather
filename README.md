🌦️ WeatherWand

A simple and dependable weather application that fetches real-time weather details using the OpenWeatherMap API.
The interface keeps things straightforward—search by city or use your current location, and the app presents temperature, humidity, pressure, and cloudiness in a tidy layout.

📌 Features

City-based Weather Search
Enter a city name to retrieve its live weather report.

Live Location Weather
Uses the browser’s geolocation to fetch your local temperature and conditions.

Clear & Structured UI
Weather icon, country flag, temperature, description, and stats are all neatly displayed.

Graceful Error Handling
Invalid city names or API issues trigger a simple shake animation to alert the user.

🛠️ Tech Stack

HTML5 for structure

CSS3 (modern gradients, shadows, responsiveness)

JavaScript (Fetch API) for API calls and DOM updates

OpenWeatherMap API for weather data

FlagsAPI for displaying country flags

📂 Project Structure
WeatherWand/
│── index.html      # Main UI structure
│── style.css       # Styling and layout
│── app.js          # Logic and API integration
│── weather.png     # Favicon


Each file contributes directly to the app’s functionality:

index.html lays out the form, weather display section, and footer. 

index

style.css handles the gradient background, card design, animations, and responsive layout. 

style

app.js fetches weather data, manages search, handles geolocation, and displays results. 

app

🚀 How to Run

Download or clone this repository:

git clone https://github.com/yourusername/WeatherWand.git


Open index.html in any modern browser.

Replace the API key in app.js with your own from
https://openweathermap.org/api

let id = 'YOUR_API_KEY_HERE';


You're all set.

📸 Screenshot

(Add your screenshot here if you want)
You can use weather.png included in the repo.

⚠️ Notes

Location accuracy depends on the browser and user permissions.

API usage is rate-limited on free OpenWeatherMap keys, so heavy usage might need a paid plan.

🤝 Contribution

Pull requests are welcome. If you spot an issue, feel free to open one.

📜 License

This project is open-source and available under the MIT License.
