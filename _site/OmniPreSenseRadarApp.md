# Speed Reporting Radar Gun - OmniPreSense

[Playstore](https://play.google.com/store/apps/details?id=com.omnipresense.radarApp&hl=en_US){:target="_blank"}

This is an Android app that turns any mobile device into a radar gun. Users can connect their devices to any OPS board using the OTG cable to track a car's speed.

The app can also take photos of cars that are speeding, then overlaying photos with information and save them with users' permission. Last functionality the app can do is uploading the photos taken onto the company's Twitter account.

## Main Features:
 - Displays cars' speed in real-time.
 - Captures photos when cars tripped over the speed limit.
 - Overlays photos with information such as date/time, cars' speed, lat/lng, address.

## Notable performance specifications:
 - Utilizes asynchronous threading to give users a smooth experience.
 - Pinpoints user's location by utilizing Google Maps API.
 - Captures photos while the app is running in the background.
 - Provides a mini-camera view when the app is minimized. [In development]
 - Query RESTful req/res with Twitter API.

## Technologies/Tools:
 - Android SDK
 - Google Maps API
 - Twitter API
 - Retrofit
 - OkHttp
 - Signpost
 - Fotoapparat (for camera operations)
 - Google Material Design
 - JavaMail
 - rxJava

## Demo
<iframe width="560" height="315" src="https://www.youtube.com/embed/d59eEPpTZIU" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Screen shots:

{% include image.html url="images/SpeedReportingRadarGun/MainScreen.png" description="Speed Recorded with Camera View" %}
<br>
{% include image.html url="images/SpeedReportingRadarGun/SecondScreen.png" description="Configurations for OPS Board" %}

[Back](/)