# Magnet Polarity Detection using STM32
This project detects the ***north or south*** polarity of a magnet using an analog magnetic sensor connected to STM32 microcontroller. The analog output is processed through ADC, and the result is displayed on a OLED Display.

---

## Components Required
### Software Required
1. STM32CubeIDE
### Hardware Required
1. Hall Effect Sensor (SS49e)
2. Analog to Digital Convertor (ADC0808)
3. STM32F103C8T6
   
---

## How to Use
1. Clone or download this repository.
2. Open the project in STM32CubeIDE.
3. Connect the following hardware:
4. Magnetic sensor → ADC pin
5. OLED (SSD1306) → I²C pins (SCL/SDA)
6. Build and flash the code to your STM32 board.
7. Bring a magnet close to the sensor →
8. OLED shows NORTH for North pole & SOUTH for South pole

---
## Video

https://github.com/user-attachments/assets/06017df8-d826-443d-87d9-d45764009d59


