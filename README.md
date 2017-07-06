# DHT11
##Load the Adafruit code to your python library
https://github.com/adafruit/Adafruit_Python_DHT

* Add logDHT11.py to your python directory

* Put the following code in the logSensors.py file, so cron will pick this up.

* At the top, with the other import statements, add:
  
> from logDHT11 import logTempHumid

* Add to code section:

> logTempHumid()
