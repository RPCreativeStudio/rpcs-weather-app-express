# Build a Weather API Express Server plus Hide Your API Keys, Demo Rate Limiting & Caching
Server used for hiding API keys, rate limiting and caching. This uses the [OpenWeather API](https://openweathermap.org/api) but you can easily change it to whatever public API you are using

## Usage

### Install dependencies

```bash
npm install
```

### Run on http://localhost:1010

```bash
npm run dev
```

### Add public API info

Rename **.env.example** to **.env** and edit the values

If the public API URL is **https://api.openweathermap.org/data/2.5/weather?q={city}&appid={APIkey}**

- API_BASE_URL = "https://api.openweathermap.org/data/2.5/weather"
- API_KEY_NAME = "appid"
- API_KEY_VALUE = "YOUR API KEY FROM OPENWEATHERMAP"

You can add on any other query params as needed when hitting the /api endpoint such as https://yourdomain/api?q=Manila without having to add your key in the client

- Add new routes as you see fit
- Change rate limiting and caching to desired values

This project demonstrates the use of these technologies - express, express-rate-limit, apicache, heroku, heroku cli, github cli, github, postman, node, fetch, cors, dotenv, needle

Find more demo at https://www.youtube.com/c/PinoyKowder/videos

