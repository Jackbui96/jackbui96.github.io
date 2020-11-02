# WhereIsMyCar - Graduating Project

[Github](https://github.com/Jackbui96/WhereIsMyCar){:target="_blank"}

An Android app that helps SJSU students locate where they parked their car. When students left the car, a camera will capture a photo and store it in the database. The app then crop the photso for the license plate string. Students after school can open the app and enter their license plate for the location.

The app uses Google ML Kit to identify the car's license plate and store it in Firebase's NoSQL. Additionally, students can create an account and save their lincense plate for future uses.

### Main Features:
 - Displays the car's location upon request.
 - Simulates the croping process to get the license plate characters.
 - Authenticates with user name and password.
 - Shows 3 main parking locations to students.

### Notable performance specifications:
 - Utilizes ML Kit API to confidently identify license plate.
 - Stores image file sercurely using Firebase Cloud Storage.
 - Stores and authenticates students using Firebase Authentication.
 - Shows main parking locations using pins and Google Maps API.
 - Quick authenticates using Google Sign-in.
 - Captures photos while the app is running in the background.
 - Provides a mini-camera view when the app is minimized. [In development]
 - Query RESTful req/res with Twitter API.

### Technologies/Tools:
 - Android SDK
 - Google Maps API
 - Firebase Cloud Storage
 - Firebase OAuth2

## Screenshots
{% include image.html url="/images/WhereIsMyCar/ThirdScreen.png" description="License Plate Recognition" %}
{% include image.html url="/images/WhereIsMyCar/ForthScreen.png" description="Result Queried" %}
{% include image.html url="/images/WhereIsMyCar/FifthScreen.png" description="Authentication" %}

[Back](/index)