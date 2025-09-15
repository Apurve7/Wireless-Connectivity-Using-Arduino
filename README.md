# Wireless-Connectivity-To-Arduino

This project turns an ESP8266 into a standalone Wi-Fi access point and web server. You can connect to its Wi-Fi network with your phone or computer and control the board's built-in LED from a simple web page.

Functionality 
This code configures the ESP8266 to operate in Software Access Point (Soft AP) mode. This means it creates its own Wi-Fi network instead of connecting to an existing one.

Wi-Fi Access Point: The ESP8266 broadcasts a Wi-Fi network with the SSID "WIFI_ESP8266_Pratik" and the password "12345678".

Web Server: Once connected to this network, the ESP8266 serves a basic HTML web page.

LED Control: This web page displays the current status of the built-in blue LED and provides "ON" and "OFF" buttons. Clicking these buttons sends a request back to the ESP8266, which then toggles the LED accordingly.

The built-in LED on most ESP8266 boards is active-low, meaning sending a LOW signal turns it ON, and a HIGH signal turns it OFF. The code handles this logic.

Hardware Requirements 🔩
An ESP8266-based development board (e.g., NodeMCU, Wemos D1 Mini).

No other components are needed as the project uses the board's built-in Wi-Fi and LED.

Software & Board Setup 💻
Arduino IDE

ESP8266 Board Support: You must add ESP8266 board support to your Arduino IDE.

Go to File > Preferences.

In the "Additional Boards Manager URLs" field, paste this URL: http://arduino.esp8266.com/stable/package_esp8266com_index.json

Go to Tools > Board > Boards Manager...

Search for "esp8266" and install the package by "ESP8266 Community".

This project turns an ESP8266 into a standalone Wi-Fi access point and web server. You can connect to its Wi-Fi network with your phone or computer and control the board's built-in LED from a simple web page.

Functionality 🌐
This code configures the ESP8266 to operate in Software Access Point (Soft AP) mode. This means it creates its own Wi-Fi network instead of connecting to an existing one.

Wi-Fi Access Point: The ESP8266 broadcasts a Wi-Fi network with the SSID "WIFI_ESP8266_Pratik" and the password "12345678".

Web Server: Once connected to this network, the ESP8266 serves a basic HTML web page.

LED Control: This web page displays the current status of the built-in blue LED and provides "ON" and "OFF" buttons. Clicking these buttons sends a request back to the ESP8266, which then toggles the LED accordingly.

The built-in LED on most ESP8266 boards is active-low, meaning sending a LOW signal turns it ON, and a HIGH signal turns it OFF. The code handles this logic.

Hardware Requirements 🔩
An ESP8266-based development board (e.g., NodeMCU, Wemos D1 Mini).

No other components are needed as the project uses the board's built-in Wi-Fi and LED.

Software & Board Setup 💻
Arduino IDE

ESP8266 Board Support: You must add ESP8266 board support to your Arduino IDE.

Go to File > Preferences.

In the "Additional Boards Manager URLs" field, paste this URL: http://arduino.esp8266.com/stable/package_esp8266com_index.json

Go to Tools > Board > Boards Manager...

Search for "esp8266" and install the package by "ESP8266 Community".

How to Use 
Open the Code: Open the provided code in the Arduino IDE.

Select Your Board: Go to Tools > Board and select your specific ESP8266 board (e.g., "NodeMCU 1.0 (ESP-12E Module)").

Upload the Code: Connect your ESP8266 to your computer and upload the sketch.

Connect to the Wi-Fi: Use your smartphone or computer to search for new Wi-Fi networks. Connect to the network named "WIFI_ESP8266_Pratik" using the password "12345678".

Open a Web Browser: Once connected, open a web browser (like Chrome, Firefox, or Safari).

Navigate to the Server: In the address bar, type in the default IP address for the ESP8266's access point: 192.168.4.1 and press Enter.

Control the LED: The web page will load, showing you the "LED ON" and "LED OFF" buttons. Use them to control the blue LED on your ESP8266 board.


