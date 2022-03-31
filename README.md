# WDI2022

This example firmware that creates HomeKit compatibile accessory using Espressif HomekKit SDK and their ESP-IDF RTOS enviroment. More info on using these tools can be fouund here: https://github.com/espressif/esp-homekit-sdk 

This code works on WeMos mini ESP8266 board with DHT11 and relay shields. It sets a HomeKit accessory with several services as Fan, Themperature and Humidity, as well as provides some internal logic to demonstrate way to feedback external events to HomeKit assessory using HAP protocol.
