#Smart Building Security and Access Control System

##Project Overview

The Smart Building Security and Access Control System is an embedded security project based on the LPC2129 ARM7 microcontroller.

The system uses RFID for user authentication and a 4×4 keypad for password-based authentication.

A PIR sensor is used to detect human motion near the entrance, while a magnetic door sensor monitors the door status. The DS1307 RTC maintains the date and time, and an I2C EEPROM is used to store important system data and security events.

A 16×2 LCD displays system status and messages to the user. After successful authentication, a relay and electromagnetic door lock control access, while a servo motor provides automatic door operation.

The project combines these modules to provide a simple, reliable and automated security and access-control system.

##Components Used

- LPC2129 ARM7 Microcontroller
- RC522 RFID Reader
- 4×4 Matrix Keypad
- PIR Motion Sensor
- Magnetic Door Sensor
- DS1307 RTC
- I2C EEPROM (AT24C256)
- 16×2 LCD
- Relay Module
- Electromagnetic Door Lock
- Servo Motor
- LEDs
- Buzzer

##Software Used

- Embedded C
- Keil µVision
- Flash Magic

##Build and Run

1. Open the project in Keil µVision.
2. Select the LPC2129 device.
3. Add all required ".c" files.
4. Add the required header files.
5. Build the project.
6. Program the LPC2129 using Flash Magic.
7. Test the RFID, keypad, PIR, RTC, EEPROM, door sensor and access-control functions.

##Features

- RFID authentication
- Keypad password authentication
- PIR motion detection
- Door status monitoring
- RTC-based date and time
- EEPROM data storage
- Automatic door locking and unlocking
- Servo-based automatic door control
- LCD status display
- LED and buzzer indications
- Modular Embedded C drivers

##Project Objective

The main objective of this project is to develop a secure and automated building access-control system using the LPC2129 ARM7 microcontroller. The system authenticates users, controls door access, monitors security conditions and stores important security data.

##Team Members
- V25BE8M2(MUNAGAPATI VENKATASAI)
- V25BE8K2(MADIHA KANDUKURI)
- V25BE8B5(BHAGYASHREE MANE)
