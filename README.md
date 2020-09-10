# Microbit-PCA9685
This is a c++ library for the PCA9685 connected to a Microbit

There are only 3 commands:
```c
PCA9685 LedController1(64);
//LedController1: Self chosen name
//64: I2C adress of the PCA9685

LedController1.init(1500);
//LedController1: The controller you have defined
//1500: the frequency set for the pwm on the PCA9685

LedController1.setPinPulseRange(15, 100);
//LedController1: The controller you have defined
//15: the pin-number
//100: the percentage of the pwm
```
