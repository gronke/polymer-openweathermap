Polymer Element: openweathermap
===============================

A Polymer element that queries data from OpenWeatherMap API. Input can be either the name of a city or the coordinates of a location.

Examples
--------

```
<openweathermap-weather-coordinates lat="37.773972" lng="-122.431297" result="{{result}}" />
```

```
<openweathermap-weather-city city="San Francisco, US" result="{{result}}" />
```

Demo
----

<!--
```
<custom-element-demo>
  <template>
    <link rel=”import” href=”polymer-openweathermap-coordinates.html”>
    <openweathermap-weather-coordinates
      lat="37.773972"
      lng="-122.431297"
      result="{{result}}">
    </openweathermap-weather-coordinates>
    <pre>{{result}}</pre>
  </template>    
</custom-element-demo>
```
-->

```html
<openweathermap-weather-coordinates
  lat="37.773972"
  lng="-122.431297"
  result="{{result}}">
</openweathermap-weather-coordinates>
<pre>{{result}}</pre>
```
