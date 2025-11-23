# Materials:
	•	1 x 4-channel 16-bit ADC (ADS1115) —  AZ-delivery
	•	1 x ESP32-WROOM dev board 
	•	Biophotovoltaic unit

# Software:
	•	Arduino IDE
	•	Adafruit ADS1115 library
	•	ESP32 by Espressif Systems add-on in IDE board manager

# Circuit wiring:
| ADS1115 | ESP32|
|---------|------|
| SDA     | 21   |
| SCL     | 22   |
| GND     | GND  |
| VDD     | 3.3V |

| BPV     | ADS1115 |
|---------|---------|
|anode(-) | GND     |
|cathode(+)| A0     |

![Datalogger wiring](https://github.com/marialilokyee/phytonet/blob/main/Photos/FigS2_Paper%20Figures_Biomimetics.jpg)
