#### Title of Project: Illegal border crossing detection system Based on cloud infrastructure

(1.0) Project Introduction
	 Rural areas, such as houses and a country's borders, face many security problems. Although there is fancy or boundary for the safety purpose it’s not enough for security. In this era, we have a  many technology for security but there is no specific technology for home and country border security. And now we are working on this kind of problem. In our project, we working with NodeMCU esp32. NodeMCU is an open-source IoT platform. It includes firmware that runs on the ESP32 Wi-Fi SoC from Espressif Systems, and hardware that is based on the ESP-12 module.NodeMCU esp32 wifi module is working with an infrared sensor(IR). The detection range of the IR sensor is around 2 cm to 30 cm. The sensor module is interfaced with Arduino having an IO voltage level of 3.3V to 5V. First of all, If an object is detected by the IR sensor then the signal passes to the NodeMCU esp8266 wifi  module. NodeMCU will check whether the wifi is connected or not. After that, the NodeMCU esp8266 wifi module will check the signal from the IR sensor. Then the NodeMCU esp8266 wifi module analyzes the signal through Arduino IDE and sends a http request to the Heroku cloud server. When the user needs to see the touch history, then the web sends a request to a  cloud server. Cloud servers synchronize the data from the database and respond to the web server. Finally, the user can see details of the object that crosses the IR sensor.

(2.0) Project Methodology
      In this project, we use IR sensor, nodeMCU, Heroku cloud server, nodejs app engine, android studio. NodeMCU is always connected to the server by wifi service and can send HTTP requests to the server. This notification is stored in the server database and server notice center update. When the server updates, then this update notification is sent to the user. Users who have an Android app, web, and Android app immediately see this notification. 

(2.1) System Diagram         
      <img src="diagram.png"/> 
      Figure: System process diagram

(2.2) System Example
      <img src="flowchart.png"/> 
(2.3) Realtime detection
      ![unnamed](https://github.com/user-attachments/assets/3bebf064-e336-43df-8e3e-f65eb0c205c0)
      ![unnamed (1)](https://github.com/user-attachments/assets/9d80d5db-2f5f-4d04-a452-63985824ddf6)





