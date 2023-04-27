Connect the SW 420 vibration sensor to the Arduino Nano as follows:
VCC pin of the sensor to 5V pin of the Arduino Nano
GND pin of the sensor to GND pin of the Arduino Nano
D0 pin of the sensor to pin 2 of the Arduino Nano
Connect the ADXL345 accelerometer to the I2C bus of the Arduino Nano as follows:
VCC pin of the accelerometer to 5V pin of the Arduino Nano
GND pin of the accelerometer to GND pin of the Arduino Nano
SDA pin of the accelerometer to A4 pin of the Arduino Nano
SCL pin of the accelerometer to A5 pin of the Arduino Nano
Connect the I2C module to the Arduino Nano as follows:
VCC pin of the module to 5V pin of the Arduino Nano
GND pin of the module to GND pin of the Arduino Nano
SDA pin of the module to A4 pin of the Arduino Nano
SCL pin of the module to A5 pin of the Arduino Nano
Connect the LCD crystal 16x2 to the I2C module as follows:
GND pin of the LCD to GND pin of the module
VCC pin of the LCD to VCC pin of the module
SDA pin of the LCD to SDA pin of the module
SCL pin of the LCD to SCL pin of the module
Download and install the necessary libraries for the ADXL345 accelerometer and the LiquidCrystal_I2C library for the LCD display.

Use the modified code provided in the previous answer that uses a fixed threshold value for detecting vibrations.
