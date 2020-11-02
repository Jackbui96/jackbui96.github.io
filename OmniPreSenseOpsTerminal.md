# OpsTerminal - OmniPreSense

*This app is still in development and havent yet published.*

This is an Ops Provision Android app. The app's purposes is to provides the GUI interface for engineers out of the field. With the help of the app, engineers can flexibly configurate through long distances. Last and not least, with the UI interface, engineers can switch and config multiple boards.

The app uses MQTT protocol to establish connection between the app and the board. The app can connect to any custom MQTT server securely with built-in authentication service. 

## Main Features:
 - BLE/MQTT commnunication
 - Provisioning
 - Save logs as csv file
 - Capture photos when the object tripped over the speed limit.
 - Overlay photos with information such as date/time, the object's speed, lat/lng, address.

## Notable performance specifications:
 - Gives users a smooth experience by utilizing asynchronous threading.
 - Able to get the user's location by utilizing Google Maps API.
 - Capture photos while the app is running in the background.
 - The app is able to minimize itself. This will let the user know where to point their device while the app is in the background.

## Technologies/Tools:
 - Android SDK
 - Paho MQTT Android API
 - Espressif ToolChain
 - Espressif BluFi API
 - Google Material Design
 - OpenCSV API
 - Websocket

## Screen shots:

{% include image.html url="images/OpsTerminal/HomeScreen.png" description="Speed/Range Recorded" %}
{% include image.html url="images/OpsTerminal/TerminalScreen.png" description="Terminal Screen" %}
{% include image.html url="images/OpsTerminal/ThirdScreen.png" description="Configuration Screen" %}
{% include image.html url="images/OpsTerminal/WiFiConfig.png" description="BLE/WiFi Connection" %}

[Back](/index)