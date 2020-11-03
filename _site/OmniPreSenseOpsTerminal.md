# OpsTerminal - OmniPreSense

*This app is still in development and havent yet published.*

This is an OPS Provision Android app. The app's purpose is to provide the GUI interface for engineers out of the field. With the help of the app, engineers can flexibly configure through long distances. Last and not least, with the UI interface, engineers can switch and config multiple boards with ease.

The app uses the MQTT protocol to establish a connection between the app and the board. The app can connect to any custom MQTT server securely with a built-in authentication service.

## Main Features:
 - Records speed/range in real-time
 - Configures OPS board through the terminal
 - Subscribes/Publishes data via MQTT
 - Collects and exports data to csv

## Notable performance specifications:
 - Reliably establishes the connection when either is disconnected.
 - Ultilize concurrent threading to chain commands.
 - Gives users a smooth experience by utilizing asynchronous threading.
 - Addes authentication for security.

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
<br>
{% include image.html url="images/OpsTerminal/TerminalScreen.png" description="Terminal Screen" %}
<br>
{% include image.html url="images/OpsTerminal/ThirdScreen.png" description="Configuration Screen" %}
<br>
{% include image.html url="images/OpsTerminal/WiFiConfig.png" description="BLE/WiFi Connection" %}

[Back](/)