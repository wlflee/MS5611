# Welcome to MS5611 library
## MS5611-01BA Pressure Sensor - ARDUINO

This is a C++ library for barometric pressure sensor MS5611-01BA. 
My motivation for writing this library was fact that some existing libraries had a bug
in the pressure reading compensation routine for low temperatures. As a result, 
the pressure readings at low temperatures (< ~12C) were completely off. 

The library was tested for pressure stability in the temperature range of -11C - 50C
using regular kitchen fridge and oven. In this temperature range, the measured variance 
of the absolute altitude at the 200m above the see level was estimated at cca 20m (600ft).

Therefore, be aware of using MS5611 in temperature unstable environments where device rely on absolute
altitude.
