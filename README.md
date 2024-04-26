<h1>eeeZeeeSensor sends data measurements to eeeZeeeServer. Minimal demo. Python 3. Raspbian Bullseye. </h1>

<h3>CO2. Temperature. Humidity. Air Pressure.</h3>

<h3>Sensors:</h3>

- BME280 - I2C

- Senseair K30 - serial

- RTC DS3231 - I2C

- LCD1602 - I2C

<h3>Commands:</h3>

start data collection: 
* <b>python sensor.py</b>

<b>NOTE: This is demo code. Data is being sent from eeeZeeeSensor to eeeZeeeServer over Flask API as an INSERT query. Consider encryption for the communication channel in your production code.</b>

All files are released under a [MIT license](https://en.wikipedia.org/wiki/MIT_License)
  
