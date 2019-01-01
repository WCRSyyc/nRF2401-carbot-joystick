# nRF2401-carbot-joystick

Demonstration remote control code for the WCRS [carbot](https://github.com/WCRSyyc/carbot) chassis.  This sketch reads analog joystick values, calculates differential steering wheel speed settings, and sends the result to an nRF2401 radio.  The code is heavily commented, and includes the ability to easily enable some debug code to report status information to serial output.

This does not implement a full featured remote control.  It is intended to provide only enough of the basics for demonstrating safe functionality and debugging.  The intent is for the carbot builder to enhance this for their own projects.  Providing learning opportunities, including for programming, is part of the goals of the WCRS.
