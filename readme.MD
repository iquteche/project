<b>Library micropython SHT30 Humidity and Temperature Sensor</b>

<img src="https://img.joomcdn.net/3a1cd15c26ae7bc1ed54a1d72cf8c305cc3bdae7_original.jpeg" alt="Girl in a jacket" width="500" height="400">

usage:

from sht30 import SHT30
import time

sensor = SHT30()


while True:
  temperature, humidity = sensor.measure()

  print('Temperature:', temperature, 'ºC, RH:', humidity, '%') 




