# Smart Window Solution for Libraries

## Overview
This project is designed to automate the control of windows and shades in a library setting based on environmental factors such as temperature, light intensity, and rain. Actuators including stepper motors, servo motors, and a DC fan work together to ensure energy efficiency and comfort. The system is controlled through a LabVIEW program, with precise data acquisition managed by NiDAQmx.

## Introduction
The Smart Window Solution is built to respond to changing environmental conditions. It leverages temperature, light intensity, and rain sensors to dynamically adjust window positions, shades, and lighting. The system helps maintain optimal indoor conditions while reducing the need for manual intervention.

## Sensors Used
1. **Temperature Sensor**: Custom-built using a PTC transmitter, calibrated with a thermometer for accurate temperature readings.
2. **Light Intensity Sensor**: Developed using an LDR, calibrated with a luxmeter to detect varying light conditions.
3. **Rain Sensor**: Detects the presence of rain, preventing the windows from opening during rainfall.

## Functionalities
1. **Window Opening Mechanism**: 
   - The window will open if:
     - The light intensity is **more than 200 lux**,
     - It is **not raining**, and
     - **Someone is detected on the chair**.
   - All three conditions must be satisfied for the window to open. If any condition fails, the window will automatically close.

2. **Shade Control**:
   - If the light intensity is **more than 600 lux**, the shade will open to block excessive sunlight.

3. **Lighting System**:
   - If the light intensity drops **below 200 lux**, the lights in the room will automatically turn on to provide sufficient illumination.

4. **Cooling System**:
   - When the room temperature exceeds **30°C**, the fan will start to cool down the room by circulating air.

## Our Team

![IMG_6350](https://github.com/user-attachments/assets/048861a1-6362-4abc-ad2f-158cf08376a9)

## LabView
![Screenshot (280)](https://github.com/user-attachments/assets/e8b65f21-5a53-41c8-9008-c3abddd7feac)
![Screenshot (281)](https://github.com/user-attachments/assets/1aba4a21-8381-45dc-b8e3-09a655ddcf51)
![Screenshot (282)](https://github.com/user-attachments/assets/030ac8f6-a688-4693-88bb-951603eb0c0d)
![Screenshot (283)](https://github.com/user-attachments/assets/71c7e0ad-a701-4d1f-9153-c97cc59c2ebc)
![Screenshot (284)](https://github.com/user-attachments/assets/e97ee525-030f-4f08-a2fe-b9e9248bb105)

