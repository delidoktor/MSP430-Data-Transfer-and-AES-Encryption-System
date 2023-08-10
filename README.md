# MSP430-Secure-Embedded-Communication

# MSP430 Data Transfer and AES Encryption System

This project demonstrates a three-stage data processing pipeline using MSP430 microcontrollers:

1. **Data Collection:** An MSP430 reads data from a sensor.
2. **Encryption and First Transfer:** The collected data is encrypted using the AES encryption algorithm. This encrypted data is then transmitted to a second MSP430 via the ESP8266 WIFI module.
3. **Decryption and Second Transfer:** The second MSP430 decrypts the received data and forwards it to a third MSP430 using the same WIFI module.
4. **Display:** Upon receiving the data, the third MSP430 displays it on an LCD.

## Components Used:
- 3x MSP430 microcontrollers
- ESP8266 WIFI module
- AES Encryption algorithm
- LCD Display







