# Amayadori

Amayadori (雨宿り) is an experimental anonymous chat that can only be used when it's raining where you are. The prototype uses Firebase and the OpenWeatherMap API to demonstrate the concept described in the included design document.

## Running the prototype

1. [Create a Firebase project](https://firebase.google.com/) and enable **Firestore** and **Anonymous Authentication**.
2. Obtain an API key from [OpenWeatherMap](https://openweathermap.org/).
3. Download or clone this repository and open `index.html` in your browser.
4. When prompted, enter your weather API key and allow location access.

The chat room appears only when the current weather conditions indicate rain. Once the rain stops, the room closes automatically and all chat logs are removed.
