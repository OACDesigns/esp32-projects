# Extractor Fan ESP32

**NB:** at the moment it isn't installed as an esphome project, but rather using [ESPEasy](https://github.com/letscontrolit/ESPEasy) and their web-based flasher. It communicates over MQTT, and is integrated to HA as a package. 


### CC1101 Pin Layout
| CC1101 pin | ESP Pin  | Description |
|:-----     |:------:   |------:      |
| 1 - GND   | GND       | Ground      |
| 2 - VCC   | VCC       | 3.3v        |
| 3 - GDO 0 | N/A       | Unused      |
| 4 - CSN   | 15=D8     | Chip select / (SPI_SS)  |
| 5 - SCK   | 14=D5     | Clock pin   |
| 6 - MOSI  | 13=D7     | Data input to CC1101    | 
| 7 - MISO  | 12=D6     | Data output from CC1101 / serial clock from CC1101  |
| 8 - GDO 2 | 05=D1     | Interrupt pin           |

