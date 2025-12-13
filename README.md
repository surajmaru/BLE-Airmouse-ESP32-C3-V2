# BLE Air Mouse ESP32 C3 V2

## This is the upgraded version of the previous air mouse which was made using the esp32 s3, In this current version i have used an esp32 c3 super mini and also made several changes which has changed my airmouse alot and functions even better than ever!

# Features
- its extremely handy to use.
- battery capacity is big so no worries for long usage.
- has the left right click and scrolling feature too.
- very easy to use and compact.
- easy to make you own!

# Schematics
<img width="1904" height="875" alt="Screenshot 2025-12-13 171910" src="https://github.com/user-attachments/assets/3a1dcb29-0f51-432c-bf17-fde488cb1661" />

# Connections
| Battery (1S Li-ion) 3.7V| Boost Converter 5V |
|--------------------|-------------------------|
|    +               |  +                      |
|    -               |  -                      |


| Boost Converter 5V | ESP32 S3 Pin |
|---------------------|-------------|
|    +                |  VCC        |
|    GND              |  GND        |
 

| ESP32 S3 Pin | MPU6050 |
|--------------|---------|
| 5V(VCC)      |  VCC    |
| GND          |  GND    |
| 10           |  SCL    |
| 11           |  SDA    |


| ESP32 S3 Pin | Button |
|--------------|--------|
| GND          |  GND   |
| 4            |  BTN 1 |
| 5            |  BTN 2 |
