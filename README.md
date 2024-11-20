# WiFi Pishing Tool Based On ESP-32🔪

This project creates a WiFi login portal for the mentioned SSID Network , allowing victims to log in with their email and password to gain access to the fake network. The portal runs on an ESP32 board and utilizes the `WiFiMulti`, `DNSServer`, and `WebServer` libraries to handle network requests and DNS spoofing.

---

## ⚠️ Ethical Declaration 

The **ESP-32-Pishing-Tool** project is designed for educational and demonstration purposes only. The goal of this project is to showcase network management concepts, including web-based login authentication and user interaction through a local network. It is not intended for any malicious use or unauthorized access to private networks.

By using or modifying this project, users agree to the following ethical guidelines:

1. **Educational Use Only:** This project is intended to demonstrate network-related concepts in a controlled, ethical environment. It should not be used to access or interfere with networks, devices, or services without proper authorization.
   
2. **Respect for Privacy:** Any collected data, including user credentials, should be handled with care. This project should not be used to collect sensitive or personal information without explicit consent from all users involved.

3. **Compliance with Laws:** The use of this project must comply with local laws and regulations regarding network access, data privacy, and cybersecurity.

4. **No Malicious Activity:** Users should not deploy this project in ways that could harm others, such as by intercepting or exploiting data from unauthorized users or systems.

5. **Responsible Development:** When adapting or deploying this project, it is important to consider the ethical implications of its use. Developers are encouraged to build solutions that promote security, privacy, and responsible behavior online.

The creator of this project disclaims any liability for any misuse, and users should take full responsibility for the application and deployment of the project.


## 🔧 Features

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

---

## 🌱 Contributing

Contributions are welcome! If you have suggestions for improvements or features, feel free to fork the project and submit a pull request. Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Make your changes and commit them (`git commit -am 'Add new feature'`).
4. Push the changes to your forked repository (`git push origin feature-branch`).
5. Submit a pull request!


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

