# SmartTank
Monitor the tank conditions, such as in and out tank temperature and water clarity, with a RaspberryPi.

## Sensors
* DHT22: Thermal and humidity sensor. The library is Adafruit library.
* DS18B20: Water proof thermal sensor

## Work flow on Pi
1. Call the python code.
2. Creat txt files for DHT22 and DS 18B20 whose name contains the creating time.
3. Call DHT22 and DS18B20 every 10 seconds and takes the median attach to a txt file. 

## Work flow on Server
1, fetch the data from Pi. 
2, Call python codes that visualize the data.

## Reference
* For DHT22 config: https://www.youtube.com/watch?v=IHTnU1T8ETk
* For DS18B20 config: 

