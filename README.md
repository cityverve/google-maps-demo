# google-maps-demo

This is a demonstration of using the CityVerve API together with Google Maps

Click [here](https://cityverve.org.uk/what-is-cityverve/) to learn more about CityVerve.

Click [here](http://developer.cityverve.org.uk/) to go to the CityVerve Developer Portal.

Click [here](http://developer.cityverve.org.uk/showcase) to see a showcase of working CityVerve apps (including this demo).

Click [here](https://developers.google.com/maps/) to go to the Google Maps developer portal.

## Instructions

In order to get this demo working for yourself, you simply need to clone the repo and host the files within your web-server of choice.

Before it will work, however, you need to make **two modifications**:

### CityVerve API Key

At the top of the JavaScript file, you will find the following line of code:

```javascript
const API_KEY = 'YOUR-KEY-HERE';  // cityverve api key
```

You need to replace the string **YOUR-KEY-HERE** with your own personal _CityVerve API key_. You can get a key (for free) at our [Developer Portal](http://developer.cityverve.org.uk/home). Just follow the steps in our [Getting Started](http://developer.cityverve.org.uk/get-started) guide.

### Google Maps API Key

Towards the bottom of the HTML file, you will find the following line of markup:

```html
<script src="https://maps.googleapis.com/maps/api/js?key=YOUR-KEY-HERE&callback=initialise" async defer></script>
```

You need to replace the string **YOUR-KEY-HERE** with your own personal _Google Maps API key_. You can get a key (for free) at the [Google Maps Developer Portal](https://developers.google.com/maps/).


_Have fun, and [please do share](https://cityverve.org.uk/contact/) any cool apps that you make with the CityVerve API._
