# Weather app by Kloveazaks
## View UI App
==============

<img src="imagesForGithub\screenUIApp.jpg" height="500px"></img>


```
val CITY: String = "ukraine,donetsk"
val API: String  = "xxxxxxxxxxxxxxxxxxxxx"

response = URL("https://api.openweathermap.org/data/2.5/weather?q=$CITY&units=metric&appid=$API").readText(
                    Charsets.UTF_8
                )
```

## Response json

<img src="imagesForGithub\screenJson.jpg" height="70"></img>
