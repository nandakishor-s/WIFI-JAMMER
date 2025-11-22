# WIFI-JAMMER
Nanda Kishor s (24BCE1560), Harshadh Jeyaprakash (24BCE1610) ,Ganesh Raman R(24BCE1628)



An educational project to understand how WiFi jamming works in a safe, controlled environment using ESP8266.

## ⚠ Important Legal Disclaimer

> **This project is for EDUCATIONAL PURPOSES ONLY.** It should only be used in controlled, private environments for learning about wireless network security. Unauthorized use of this technology may be illegal in your jurisdiction. The developers are not responsible for any misuse of this project.

---

## 📋 Project Overview

This is a college project designed to study WiFi jamming mechanisms in a legal and ethical manner. The project demonstrates how deauthentication attacks work at the protocol level, helping students understand wireless network vulnerabilities.

---

## 🛠 Hardware Requirements

* ESP8266 Wemos D1 Mini
* USB cable for programming
* Computer with Arduino IDE

---

## 💻 Software Requirements

* Arduino IDE
* CP2102 Driver
* Required libraries (listed in installation)

---

## 🔧 Installation & Setup

1.  **Install Arduino IDE**
    * Download and install the Arduino IDE from the [official website](https://www.arduino.cc/en/software).

2.  **Install CP2102 Drivers**
    * Install the necessary USB-to-UART bridge drivers for your ESP8266 (e.g., from [Silicon Labs](https://www.silabs.com/developers/usb-to-uart-bridge-vcp-drivers)).

3.  **Configure Arduino IDE**
    * Open Arduino IDE.
    * Go to **File → Preferences**.
    * Add this URL to **Additional Board Manager URLs**:
        ```
        [http://arduino.esp8266.com/stable/package_esp8266com_index.json](http://arduino.esp8266.com/stable/package_esp8266com_index.json)
        ```

4.  **Install ESP8266 Board**
    * Go to **Tools → Board → Boards Manager**.
    * Search for "esp8266" and install the package.

5.  **Install Required Libraries**
    * Go to **Tools → Manage Libraries...**.
    * Install the following libraries:
        * `ArduinoJson` (Version 5.13.5)
        * `ESP8266 LittleFS`

6.  **Upload the Code**
    * Select your board: **Tools → Board → ESP8266 Boards → "WeMos D1 R2 & mini"**.
    * Select the correct **COM port** under the **Tools** menu.
    * Click the **Upload** button.

---

## 🚀 Usage

### Web Interface

1.  After uploading, the device will create a WiFi access point (AP).
2.  Connect to this new WiFi network from your computer or phone.
3.  Open your browser and navigate to: `http://192.168.4.1`
4.  Use the web interface to scan for networks and learn about wireless protocols.

### Features

* Network scanning
* Access point monitoring
* Educational demonstrations only

---

## 📁 Code Structure

The main components of the code include:

* **Scanning Module:** Handles network discovery.
* **Attack Module:** Manages educational demonstrations.
* **CLI Interface:** Provides command-line control.
* **Display UI:** Manages the user interface.
* **WiFi Control:** Handles all wireless operations.

---

## 🔒 Safety & Ethics

This project includes several safety features:

* Boot loop detection with auto-formatting.
* Validation for saved settings.
* Reset button functionality (hold for 5 seconds to reset).
* LED status indicators for different modes.

---

## 🌐 Documentation

For detailed documentation and advanced features, visit:
[Deauther Documentation](https://your-link-to-docs-here.com)

---

## ⚙ Configuration

Key configuration options are available in the code:

* Display settings
* CLI (Command Line Interface) enable/disable
* Web interface settings
* Autosave functionality
* LED behavior

---

## 🎓 Educational Purpose

This project helps students understand:

* WiFi protocol vulnerabilities (e.g., deauthentication frames).
* Core network security concepts.
* Ethical hacking principles and the importance of authorization.
* Wireless communication protocols at a low level.

---

## 📝 Note

This is strictly an educational tool. **Always ensure you have explicit permission** to test on any network. Use this project only in controlled lab environments for learning purposes.
