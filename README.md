# D1RobotLCDKeypadShieldArduinoUno
A custom library for D1 Robot LCD Keypad Shield for Arduino Uno and Arduino Mega

To use this library, you only need to attach the shield to your arduino and then upload the KeypadExampe.ino program. If your keypad buttons reaction is not as it should be, you need to calibrate the keypad.

To Calibrate :
1. If the Keypad is not displaying anything
    For this progblem, try to turn the potentiometer to set the brightness.
2. If the Keypad is not displaying the right button name
    For this problem, upload the KeypadCalibration.ino program. Try to press each button and remember the value range for each button that are displayed on the keypad. Edit the value in KeypadExample.ino program line 30-36.
