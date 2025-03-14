# IOT_Light_Controller
# MQTT Light Control

This project simulates an IoT device (ESP8266) that receives MQTT messages to control a light.

## Features
- Web-based UI with ON/OFF buttons
- Uses MQTT.js for publishing messages
- Python script simulates the ESP8266

## Usage
1. Run `light_simulation.py` to start listening for MQTT messages.
2. Open `index.html` in a browser.
3. Click "Turn ON" or "Turn OFF" and observe the response in the Python script.

## Requirements
- Python 3
- paho-mqtt (`pip install paho-mqtt`)
- MQTT broker (uses `test.mosquitto.org`)
