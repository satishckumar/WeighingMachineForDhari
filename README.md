# WeighingMachineForDhari

The Basis of this weighing machine is the 50 KG load cell , connected into a Wheatstone Bridge. 
The output of the sensor is connected to HX 711, load cell amplifier. 
It is then interfaced with Arduino UNO as shown in the schematics. 
Arduino is then loaded  with suitable sketch for further signal  processing and calibration. 
The value ( Weight in KG) is then displayed on the  I2C OLED Display. 
The Schematics, Construction, Connector locations , Code..etc is loaded as a separate file . 

This Project was constructed from Concepts explained in https://www.youtube.com/watch?v=LIuf2egMioA&list=WL&index=47&t=450s
The Basic code used is from https://github.com/olkal/HX711_ADC
The above basic code is modified to incorporate a 0.96" I2C OLED display .
