ESP32-Wrover I/Os

IO0: (/program), /INT
IO2: 5V enable J107 pin 1
IO3: Fan PWM
IO4: 5V I/O J108 pin 8
IO5: 5V I/O J108 pin 7
IO6: 5V output J108 pin 6
IO7: 5V output J108 pin 5
IO8: I2S1 BCLK (stereo speaker J304)
IO9: Micro SD D1
IO10: Micro SD D0
IO11: Micro SD CLK
IO12: Micro SD CMD
IO13: Micro SD D3
IO14: Micro SD D2
IO15: 5v output J108 pin 4
IO16: 5v output J108 pin 3
IO17: I2S1 WSEL (stereo speaker J304)
IO18: I2S1 DOUT (stereo speaker J304)
IO19: USB D-
IO20: USB D+
IO21: Status LED, LED output to J103 pin 2
IO38: /INT2
IO39: M_BOOT_LOAD, BNO085 motion sensor
IO40: I2C SDA, J107 pin 5
IO41: I2C SCL, J107 pin 4
IO42: /INT3, J107 pin 3
IO45: I2S0 BCLK (Microphone)
IO46: 12V power supply enable high
IO47: I2S0 WSEL (Microphone)
IO48: I2S0 DIN (Microphone)
RXD0: Serial port RX
TXD0: Serial port TX
EN: /RESET

Bootstrap:

Boot mode:  IO0  IO46
SPI Boot    1    X
Download    0    0

VDD SPI voltage:
IO45: 0 = 3.3V, 1 = 1.8V

JTAG:
IO3:  0 = JTAG pins, 1 = USB Serial/JTAG
