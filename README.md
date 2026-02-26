# ESP32_OLED_Dev_Board
# This is a learning phase design, It may not work in real life
# About
This is a custom doubled sided ESP32 dev board based on ESP32-WROOM-32D-N4, equiped with ssd1306 0.96" OLED Display and few buttons.
A I2C bus is used for the display and for the buttons five GPIO pins are used. 

Buttons Connection: 

Button      GPIO Pin

SW1   ---->  6   (Right)

SW2   ---->  7   (Down)

SW3   ---->  16  (Left)

SW4   ---->  14  (UP)

SW5   ---->  13  (OK)

For USB to UART conversion CP2102 USB to UART bridge is used.

# Exposed Pins
One SPI Bus and three GPIO pins are exposed for external device attachments

# Board Schematics
[Board Schematic.pdf](https://github.com/user-attachments/files/25577954/Board.Schematic.pdf)
<img width="1421" height="836" alt="Screenshot 2026-02-26 194605" src="https://github.com/user-attachments/assets/fd642349-fad3-4b95-b285-ea8fa14a520e" />

<img width="475" height="631" alt="Screenshot 2026-02-26 034142" src="https://github.com/user-attachments/assets/769b34a7-0260-4c6e-abad-841abcd7072c" />
<img width="464" height="654" alt="Screenshot 2026-02-26 034225" src="https://github.com/user-attachments/assets/8a1e78a4-0bcd-42e2-9212-5d95c24fd88f" />
<img width="494" height="656" alt="Screenshot 2026-02-26 034250" src="https://github.com/user-attachments/assets/57d85ee3-5071-4ff4-a5ca-bde8186fefe2" />
<img width="507" height="684" alt="Screenshot 2026-02-26 034237" src="https://github.com/user-attachments/assets/f6d4c4df-978c-4dd8-8eed-898a86855c47" />

# Board Images
<img width="674" height="797" alt="Screenshot 2026-02-26 193803" src="https://github.com/user-attachments/assets/03c77f76-53eb-4dc2-8059-b9e1c2359198" />
<img width="695" height="845" alt="Screenshot 2026-02-26 193739" src="https://github.com/user-attachments/assets/4e17ac7b-0b01-4a76-987e-40908b9b2cac" />

