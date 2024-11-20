# WiFi Pishing Tool🔪

This project creates a WiFi login portal for the mentioned SSID Network , allowing victims to log in with their email and password to gain access to the fake network. The portal runs on an ESP32 board and utilizes the `WiFiMulti`, `DNSServer`, and `WebServer` libraries to handle network requests and DNS spoofing.

## Features

- Customizable login page
- User authentication with email and password
- Dynamic display of "victims" (logged credentials)
- Options to clear logged credentials
- Simple, clean, and mobile-friendly user interface

## Installation

### Prerequisites

Before using this project, make sure you have the following installed:
- [Arduino IDE](https://www.arduino.cc/en/software)
- [ESP32 Board Support](https://github.com/espressif/arduino-esp32)
- `WiFiMulti`, `DNSServer`, and `WebServer` libraries (can be installed via Arduino Library Manager)

## Usage

- Users will see a login page where they must enter their email and password.
- After entering credentials, the user will see a message confirming their validation.
- Admins can view all logged credentials (referred to as "victims") and clear them when needed.

### Endpoints:
- `/`: Displays the login page
- `/post`: Handles the login form submission
- `/pass`: Displays the list of credentials
- `/clear`: Clears the logged credentials

## Customization

Feel free to modify the HTML, CSS, and logic to suit your needs. You can change the SSID, customize the user interface, or add more features like authentication via OAuth or database storage.

## License

This project is open-source and released under the [MIT License](LICENSE).

## Acknowledgements

- [ESP32](https://www.espressif.com/en/products/socs/esp32) for providing the hardware platform.
- [Arduino](https://www.arduino.cc/) for the development environment.
- Libraries used: `WiFiMulti`, `DNSServer`, and `WebServer`.

---

<p align="center">
  🌟 Give this project a star if you found it Informative! ⭐

  <p align="center">
    Made with ❤️ by <a href="https://github.com/rajtilak-2020">Raj</a>
</p>

