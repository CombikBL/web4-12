<!DOCTYPE html>
<html lang="uа">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Погода Онлайн</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <div class="container">
    <h1>Погода в вашому місті</h1>
    <div class="search-box">
      <input type="text" id="city" placeholder="Введіть назву міста">
      <button onclick="getWeather()">Шукати</button>
    </div>
    <div id="weatherResult" class="weather-info"></div>
  </div>
  <script src="script.js"></script>
</body>
</html>
