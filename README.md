# DHT11
#Load the Adafruit code to your python library
#https://github.com/adafruit/Adafruit_Python_DHT

#add logDHT11.py

#Put the following code in the logSensors.py file, so cron will pick this up.

#add to import statements
from logDHT11 import logTempHumid

#add to code section
logTempHumid()
