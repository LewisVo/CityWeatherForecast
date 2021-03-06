# CityWeatherForecast

![](https://media.giphy.com/media/3og0IPV5FmWqMicJNK/giphy.gif)  
  
Click [here](https://whispering-sierra-45615.herokuapp.com/) to view the live application.

### About

Weekend project that show city weather forecast. Built with react, redux and some middlewares.  
Weather info is fetched from [openweathermap](https://openweathermap.org/forecast5). Map info is from Google Map javascript API.  
*Big thanks to [Stephen Grinder](https://github.com/StephenGrider) for his awesome course and redux-simple-starter boilerplate, which simplify most setup required to run this project.*  

#### How to install/build

Unix-like OS only. For Windows you may need to alter some parts.  

```shell
$ git clone https://github.com/LewisVo/CityWeatherForecast
$ cd CityWeatherForecast
$ npm install
$ npm run start
```
Go to `localhost:8080` to view the result.  
Also, please replace the api keys in `actions/index.js`. Don't use my api keys. 

#### Deploy 

This project is currently deployed for free at https://whispering-sierra-45615.herokuapp.com/   
To deploy :

```shell
$ heroku create
$ git push heroku master
```

### License 

MIT