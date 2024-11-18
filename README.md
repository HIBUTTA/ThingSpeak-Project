ThingSpeak Smart Irrigation Project
Hi there! 👋

Welcome to the Smart Irrigation System project, an embedded solution designed to help farmers optimize water usage for crops. With this system, farmers can reduce water waste and ensure that plants receive the right amount of hydration, all thanks to a simple yet effective solution.

About the Project
Agriculture plays a vital role in our society, and water management is one of the biggest challenges in farming. This project uses a DHT11 sensor to measure temperature and humidity, along with a soil moisture sensor, to determine when it's time to water crops. The data is sent to ThingSpeak, an online platform, where it can be monitored in real-time. This makes it easier for farmers to make informed decisions about irrigation, ensuring their plants stay healthy while conserving water.

How It Works
DHT11 Sensor measures the temperature and humidity in the environment.
Soil Moisture Sensor detects the moisture level in the soil.
The data is uploaded to ThingSpeak, so farmers can check it remotely and decide when to irrigate.
Getting Started

Hardware:
NodeMCU (ESP8266)
DHT11 Temperature & Humidity Sensor
Soil Moisture Sensor
Jumper wires & breadboard

Software:
Install the DHT library for the DHT11 sensor.
Install the ESP8266WiFi library for Wi-Fi functionality.
Install the ThingSpeak library for data communication.

Setup:
Connect the sensors to your NodeMCU according to the provided circuit.
Replace the Wi-Fi credentials and ThingSpeak API keys in the code.
Upload the code to your NodeMCU, and you'll start sending data to ThingSpeak!

Installation
Clone or download this repository to your local machine.
Open the code in Arduino IDE.
Replace the Wi-Fi credentials and ThingSpeak API keys in the code.
Upload the code to your NodeMCU.
Next Steps
You can monitor the data on the ThingSpeak dashboard.
Based on the data, you can build an automated irrigation system by adding a relay to control the water pump.
If you have any questions or suggestions, feel free to reach out to me.

Happy Farming! 🌱
- Dimuthu
