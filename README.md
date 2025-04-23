# ModuCard Nav Module

Second version of the navigation module based on the new BaseModule with STM32H563VBT6 MCU.

## A navigation module is equipped with:

- **GPS RTK ZED-F9P**
- **IMU ICM-20948**
- **IMU BNO055 (mountable on rubber shock absorbers)**
- **Barometer BMP280**

![obraz](https://github.com/user-attachments/assets/0c2b05e0-30f5-411c-bce9-ebabc41eedb3)

## Used tools:

<img align="center" height="64" src="img/logos/KiCad.png">

## Features:

### Power section

- **Input voltage:** 12V from the backplane.
- **Output voltage:** 3.3V @ 0.5A.

### ST-LINK

- Built-in **ST-LINK** connected to the backplane via USB interface.
- Enables programming and debugging of the onboard MCU.

### CAN interface

- Two independent FDCAN buses: **CAN1** and **CAN2**.
- Both connect with the backplane to facilitate communication between the onboard MCU and other modules in the system.
