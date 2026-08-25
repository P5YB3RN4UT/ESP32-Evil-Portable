<p align="center">
 <img src="https://www.media-underground.net/images/wifi.png">
</p>

<h3 align="center">ESP32 EVIL PORTABLE PORTAL</h3>

<div align="center">

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

</div>

---

<p align="center"> 
This project involves creating a portable waterproof device that uses an ESP32 microcontroller to function as a fake Wi-Fi access point for use in red team cybersecurity operations.
    <br> 
</p>

## Disclaimer 
This tool is strictly for educational purposes only. The author does not take responsibility for any illegal activity undertaken from the misuse of this software.


## Introduction
This project includes source code for a Captive Portal with the following requirements:

- <b>Captive Portal</b>

  <i>Redirects all user traffic to the login page.</i>

- <b>WiFi Access Point</b>

  <i>The ESP32 acts as an open or password-protected access point.</i>

- <b>DNS Redirection</b>

  <i>Ensures all web requests go to the login page.</i>
  
- <b>Login Page</b>

  <i>HTML-based page where users enter credentials.</i>
  
- <b>Admin Panel</b>

  <i>Displays stored credentials and allows clearing logs.</i>
  
- <b>Redirect After Login</b>

  <i>Users are excluded from registration with the message "Something went wrong".</i>

## Hardware

1. ESP32-WROOM-32 (Compatible with ESP32-WROOM-32D, ESP32-WROOM-32E, ESP32-WROVER)
2. Programming Cable
3. 18650 Battery
4. 18650 Battery Holder
5. TC4056/TP4056 Charging Module
6. Waterproof Push Button Switch
7. Waterproof USB-C Socket
8. Waterproof Project Box

## Software

[ArduinoIDE](https://www.arduino.cc/en/software) - For Programming The Device.

## Operation

1. Switch on the device.
2. Connect to the WiFi access point "((TEST))" being broadcasted by the ESP32.
3. You will be redirected to the login portal.
4. Enter email and password.
5. Credentials are logged and accessible via http://8.8.8.8/admin (default password: "admin").
6. Admin can view and clear logs.

<i>...Still under construction. More details to follow.</i>

