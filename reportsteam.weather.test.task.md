## Reports Team Coding Challenge

Below is a coding challenge for you to complete. You should be able to complete this challenge in couple of evenings of effort.

### Coding Spec:
Write an asp.net mvc application which collects current weather data for interested locations and provides ability to view weather history for them.

### Limitations:
* MS VisualStudio 2010
* .Net 4.0
* ASP.NET MVC4
* MSSQL Express for data storage
* jqGrid
* DI/IoC via Microsoft.Practices.Unity
* Data access via Entity CodeFirst
* Dependencies loaded via NuGet

### Result:
ASP.NET MVC application that can be compiled and run with 2 pages:
* editable list of interested cities (locations) with current weather
* weather history for the selected city with 3 hour step


### Details:
* Weather data provider 1 [http://openweathermap.org/api](http://openweathermap.org/api)
* Weather data provider 2 [https://developer.yahoo.com/weather/](https://developer.yahoo.com/weather/)

### Samples with my auth keys:
```
curl "http://api.openweathermap.org/data/2.5/weather?_=2&q=Rostov-on-Don,ru&appid=080fa56b819976cbf04f1a71ff56c2e8" 2>/dev/null | jq .

curl "https://query.yahooapis.com/v1/public/yql?q=select%20*%20from%20weather.forecast%20where%20woeid%20in%20(select%20woeid%20from%20geo.places(1)%20where%20text%3D%22rostov-na-donu%2C%20ru%22)%20%20and%20u%3D'c'&format=json&env=store%3A%2F%2Fdatatables.org%2Falltableswithkeys" | jq .
```
