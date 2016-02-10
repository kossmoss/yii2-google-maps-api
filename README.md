# yii2-google-maps-api

The main purpose of this extension is finding coordinates by address from Google Maps API right from Yii2 application.

## Usage

```
use kossmoss\GoogleMaps\GoogleMaps;

...

$coords = GoogleMaps::coordsByAddress("Krasnodar, Russia");
```

This extension is based on php-google-map-api library from https://github.com/streetlogics/php-google-map-api

If you want to use other features from original extension, you need to use GoogleMapAPI class instead of GoogleMaps class.
Here you can find some documentation for GoogleMapsAPI class:

-  [Demos](http://www.bradwedell.com/php-google-maps-api/demos/)
-  [Google Maps V3 Documentation](http://code.google.com/apis/maps/documentation/v3/)