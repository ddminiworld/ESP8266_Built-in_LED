🔦 ESP8266 Built-in LED Blink

This project demonstrates how to blink the built-in LED on an ESP8266 development board or ESP-01 module.

The program turns the LED ON and OFF at specific intervals using the LED_BUILTIN definition provided by the ESP8266 Arduino Core.

🚀 Features
Uses the ESP8266 built-in LED
No external components required
Beginner-friendly IoT project
Demonstrates GPIO output control
Easy-to-understand Arduino code
🧰 Requirements
Hardware
ESP8266 Board (ESP-01, NodeMCU, Wemos D1 Mini, etc.)
USB-to-Serial Programmer (for ESP-01)
USB Cable
Software
Arduino IDE
ESP8266 Board Package Installed in Arduino IDE
📌 About the Built-in LED

The built-in LED is connected internally to a GPIO pin depending on the ESP8266 board.

For the ESP-01 module:

Built-in Blue LED → GPIO1 (TX Pin)
LED is Active LOW
LOW → LED ON
HIGH → LED OFF

Since GPIO1 is also used for serial transmission (TX), avoid using Serial.print() while controlling the built-in LED on ESP-01.

🔌 Circuit Diagram

No external circuit is required.

The built-in LED is already connected internally to the ESP8266 board.

ESP8266 Board
     │
     └── Built-in LED (Internal Connection)
