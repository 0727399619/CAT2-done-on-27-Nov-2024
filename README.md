<!DOCTYPE html>
<html lang="en">
<head><style>
body {
  font-family: Arial, sans-serif;
  margin: 0;
  padding: 0;
  background-color: #f3f3f3;
  color: #333;
  text-align: center;
}

.container {
  width: 90%;
  max-width: 800px;
  margin: 50px auto;
  background-color: #ddd;
  padding: 20px;
  border-radius: 10px;
  box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
}

h1 {
  color: #5c3c92;
  margin-bottom: 20px;
}

.search-form {
  display: flex;
  justify-content: center;
  margin-bottom: 20px;
  
}

#city-input {
  padding: 10px;
  width: 70%;
  border: 2px solid #5c3c92;
  border-radius: 5px 0 0 5px;
}

.search-btn {
  padding: 10px 20px;
  background-color: #5c3c92;
  color: white;
  border: none;
  border-radius: 0 5px 5px 0;
  cursor: pointer;
}

.search-btn:hover {
  background-color: #4a2f74;
}

.weather-info {
  margin: 20px 0;
}

.weather-info h2 {
  font-size: 2em;
  margin: 10px 0;
}

.current-weather {
  display: flex;
  align-items: center;
  justify-content: center;
  margin: 10px 0;
}

.current-weather .temp {
  font-size: 3em;
  font-weight: bold;
  margin-left: 10px;
}

.forecast {
  display: flex;
  justify-content: space-around;
  margin: 20px 0;
  color: purple;
}

.day {
  text-align: center;
  font-size: 0.9em;
}
.temp{
    margin-left: 10px;
}
footer{
                    padding: 0 0 10px 0;
                    border-top: 5solid rgb(175,172,172) ;
                    text-align: center;
                    color: rgb(0 0 0 0.5);
                    font-size: 13px;
                }
               
                .form-input{
                    text-decoration: solid;
                    border: none;
                    width: 70%;
                    border-color: blueviolet;
                    border-radius: 5px;
                    font-size: 20px;
                    padding: 10px 15px;
                }

                .form-button{
                    border: none;
                    background-color: rgb(123,3,123);
                    color: whitesmoke;
                    padding: 10px 15px;
                    font-size: 20px;
                    text-transform: uppercase;
                    margin-left: 5px;
                    border-radius: 9px;
                }
                .Humidity{
                    color: rgb(123,3,123);
                    font-weight: bold;
                }
               
                
                </style>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Weather Application</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Welcome to our Weather Application</h1>
    <div>
    <form action=""class="search-form"id="search-form">
        <input type="search"name="city-name"placeholder="Enter city name"
        equired class="form-input"/>
<button type="submit"class="form-button">search</button>
    </form></div>
    <div class="weather-info">
      <h2>Paris</h2>
      
      <div class="current-weather">
        <span class="icon">🌥</span>
        <span class="temp">12°C</span>
        
      </div>
      <div>
        <p>
            <span id="currenttime">
                Tuesday

                14.40
              ,
            </span>
            <span id="weatherdescription">
                scattered clouds</span>
                <br/>
                Humidity:
                <span id="Humidity"class="Humidity">
                    66</span>
                   , Wind speed:
                   <span id="windspeed">
                    4.3
                   </span>
        </p>
    </div>
    </div>
    <div class="forecast">
      <div class="day">
        <p>Mon</p>
        <p>🌦</p>
        <p>15°  19°</p>
       
      </div>
      <div class="day">
        <p>Tue</p>
        <p>🌦</p>
        <p>15°  19°</p>
       
      </div>
      <div class="day">
        <p>Wed</p>
        <p>🌦</p>
        <p>15°  19°</p>
       
      </div>
      <div class="day">
        <p>Thu</p>
        <p>🌦</p>
        <p>15°  19°</p>
       
      </div>
      <div class="day">
        <p>Fri</p>
        <p>🌦</p>
        <p>15°  19°</p>
        
      </div>
      <div class="day">
        <p>Sat</p>
        <p>🌦</p>
        <p>15°  19°</p>
        
      </div>
      <div class="day">
        <p>Sun</p>
        <p>🌦</p>
        <p>15° 19°</p>
        
      </div>
    </div>
  </div>
  
    <footer>
        
          <p> Coded by<a href="http://gihub.com/Edward"target="_blank">
                Edward Sikweya</a>and is on<a href="http://gihub.com/Edward/week7-Weather-API"
                target="_blank">Github</a>
                and hosted by
                <a href="htttp://Edwardweatherapp.netlify.app/"target="_blank">Netlify.</a>
                <br>
                The design was done using<a href="http://www.figma.com/" target="_blank">Figma</a>
            </p>
  </footer>
</body>
</html># CAT2-done-on-27-Nov-2024
