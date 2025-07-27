# AR-Navigation
An Augmented Reality Navigation App based on ARCore Cloud Anchors and the ARCore Geospatial API and implemented with SceneView.

This project was developed for a university course, so this is a technology demonstration and not a finished product.


## Setup & Usage
Clone this repository and import it into your Android Studio.

To use the app, you will need to create an account for the Google Cloud Console and activate and set up the `ARCore API` with OAuth 2.0 authentification.  
Additionally an API-Key for the `Maps SDK for Android` is required as well, which needs to be set within the `local.properties` as `MAPS_KEY`.

The application requires a simple REST-Server to store and load the routes, which is not included in this repository but can be found [here](https://github.com/morhenny/ar-navigation-server).  
The IP address to your server can be changed in the [Webservice](https://github.com/morhenny/ar-navigation/blob/master/app/src/main/java/de/morhenn/ar_navigation/persistance/Webservice.kt) class.

## Core References

https://github.com/SceneView/sceneview-android  
https://developers.google.com/ar/develop/cloud-anchors  
https://developers.google.com/ar/develop/geospatial
