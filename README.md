# Sensor
A simple Arduino Sensor/map wrapper

## Usage

1. `#include <Sensor.h>` at the top of your file
2. Instansiate with `Sensor sensor_name(pin, min_voltage, max_voltage, min_value, max_value);`
   i.e. `Sensor temperature(A0, 515, 240, 70, 98);`
3. Use the mapped value by using `sensor_name.value()`
   (or for the example, `temperature.value()`
