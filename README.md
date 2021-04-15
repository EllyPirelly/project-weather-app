# Weather App

## What is this about?
A weather app, fetching data from [OpenWeatherMap](https://openweathermap.org/api)
- sign up to OpenWeatherMap to get an API key (it's free)
- [OpenWeatherMap FAQs](https://openweathermap.org/faq)
- [OpenWeatherMap current data](https://openweathermap.org/current)

### Visuals
480px
![480px](./img/screenshots/weatherApp-480.png)
640px
![640px](./img/screenshots/weatherApp-640.png)

### Requirements
- language english
- should show weather of **fixed** location (Tiergarten, Berlin, Germany) which is pretty close to my exact location)
- based on that location, fetch/show
    - weather icon(s)
    - temperature, with possibility to toggle between °F and °C
    - weather description
    - wind speed (in km/h)
    - wind direction (compass)
    - sunrise (am, BUT shown in 24-hrs)
    - sunset (pm, BUT shown in 24-hrs)

### Tech
- HTML, SCSS, JavaScript, [parcel.js](https://parceljs.org/)
- responsive (340px min width)
- one content shift at 640px width
- Flexbox and CSS Grid
- prepared svgs re: colors

### How to run this?

- clone the repo
- cd into project
- run `npm install`
- run `parcel index.html --open`, this will fire up the server at http://localhost:1234
<!-- - to run in development mode: `npm run dev`, this will fire up the server at http://localhost:1234
- to run in production mode: `npm run build`, this will also minify your files into the `dist` folder -->
- stop the server with `control c`

### Research starting point sources
**main**
- [Video - Code Explained: Build A Weather App Using JavaScript](https://www.youtube.com/watch?v=KqZGuzrY9D4)
- [Source code to download](https://www.codeexplained.org/2020/06/Build-A-Weather-App-Using-JavaScript.html)
- [Weather Icons](https://github.com/manifestinteractive/weather-underground-icons)
**second**
- [Video - Tyler Potts: Build a Weather app using HTML, CSS & JavaScript in 2020](https://www.youtube.com/watch?v=n4dtwWgRueI)
- [Source code on GitHub](https://github.com/TylerPottsDev/weather-app-js)

## Todo
- delete translations DE as this should only be a GB version