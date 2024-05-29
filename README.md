# Robotics
IoT Based Patient Health Monitoring on  ESP32 Web Server
Now let us begin with the designing of IoT Based Patient Health Monitoring on  ESP32 Web Server. So the circuit digram for interfacing  MAX30100, DHT11 & DS18B20 with ESP32 is given below.

Iot Based Patient Health Monitoring System ESP32

All the sensor can work at 3.3V VCC. So connect their VCC to 3.3V Power Supply. Connect the GND to GND.  MAX30100 is an I2C Sensor, so connect its SDA & SCL pin to GPIO21 & GPIO22. Connect its INT pin to GPIO19 of ESP32. The output pin of DHT11 is connected to GPIO18 of ESP32. Similarly, the output pin of DS18B20 is connected to GPIO5 of  ESP32. A 4.7K pull-up resistor is connected between output pin & VCC pin of DS18B20.


![image](https://github.com/v3153/robotics/assets/93032617/d9384bce-52b9-4e5c-a732-dc3ad8ecce43)
