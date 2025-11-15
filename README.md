🛰️ WiFi Evil Twin Detector

Arduino-based system for detecting suspicious WiFi networks that may be Evil Twin attacks.
The device scans all nearby Access Points, compares SSIDs, identifies duplicates, and serves the results on a built-in web interface.

Features :

🔍 Scans nearby WiFi networks automatically
⚠️ Detects SSID duplicates (possible Evil Twin attack)
🌐 Hosts a built-in web dashboard
📡 Displays IP address in Serial Monitor
🕹️ Simple to run on Arduino IDE (ESP8266 or ESP32)
💾 Lightweight — no external servers needed

🛠️ Hardware Requirements:

ESP8266 (NodeMCU / Wemos D1 Mini) or ESP32
USB cable
Arduino IDE installed with ESP8266/ESP32 board support

📥 Installation
1.Clone this repository: git clone https://github.com/your-username/evil-twin-detector.git
2.Open the .ino file in Arduino IDE.
3.Select your board:
      Tools → Board → ESP8266/ESP32
4.Install required Arduino libraries:
      ESP8266WiFi or WiFi.h (built-in)
      ESPAsyncWebServer
      ESPAsyncTCP (ESP8266) or AsyncTCP (ESP32)
5.Upload the code to your board.
------------------------------------------------

▶️ How to Run

Open Serial Monitor (9600 or 115200 baud depending on your code).

After boot, the device will print:
Scanner Ready  
Web server running  
Open your browser and visit: http://192.168.xxx.xxx
