# Journal

## 5.16

Completed:
- Created a folder for this project
- Organized existing files into their designated spots
Challenge:
- The pre created schematics might be in a different computer / lost -> find it next time

## 5.19

Research Parts
- Gathered datasheets of all the parts
- Started a BOM to record all required parts

Researched propellers - and found the price on aliexpress is half the prince on Amazon lmao

## 5.20

Completed:
- Migrated and continued working on the schematics
    - Couldn't find the old one :(
    - Created the symbol for MPU6050 and ESCs, and also checked the connection between the Raspberry Pi and NRF.
- Continue work on BOM

## 5.21

Completed:
- Researched how to integrate the camera
    - could use ESP32-CAM
    - Pre program it using local wife -> stream a network -> power using raspberry pi
- Verified the schematics parts
    - decide to power the Cam using ESC 5V

Challenge: still not sure how the CAM works

## 5.22

Completed:
- Continue working on schematics
    - wired the majority of the parts
- Confirmed the camera would work

Challenge:
- have to figure out how to power the nrf24l01 - need some kind of power adapter to convert 5v to 3.3v

## 5.23

Completed:
- Filled the schematics parts with a background color - looks more professional
- Continue worked on BOM
    - Organized the materials and included a link to product
    - Considered the option to buy drone legs only instead of the full frame
- Started the zine page
    - design principle: show the change from v1 to v2

## 5.24

Completed
- Modified Schematics based on actual connections
    - Power MPU6050 (VCC) using 3.3v from raspberry pi pico (U1-36) instead of 5v from ESC (U6-2)
    - Do SCL and SDA from MPU6050 need a pull up from 3.3V raspberry pi pico? - both 4.7k resistors
    - used 5v to power nrf24l01
- Update footprints