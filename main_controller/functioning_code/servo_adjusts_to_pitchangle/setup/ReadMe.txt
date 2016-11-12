This setup files are for testing and verifying that the Arduino UNO is set-up correctly.
This files help to verify if the wiring is set-up correctly as well as the internal memory (EEPROM).

Please visit this webpage for further information: http://www.brokking.net/ymfc-al_main.html

---------------------------------------------------
quote:

Step 3 - Run the setup software

Remove the props, don't connect the flight battery and upload the setup program to the Arduino Uno. Open the serial monitor at 57600baud and complete the setup by executing the requested actions.

After the setup is completed all the settings are stored in the EEPROM of the Arduino.

Check question 2 on the Q&A page if you encounter any problems / errors during the setup.
Step 5 - Receiver and gyro check

To make sure that everything is working correct it's necessary to run some basic checks. Remove the props, disconnect the flight battery and upload the ESC calibration program to the Arduino. Open the serial monitor at 57600baud.
5.1 Receiver input check

Send the letter 'r' to start the receiver monitor. Now move the sticks and see if the values on the screen correspond with the movements of the sticks.

All the channels should read 1000us till 2000us with a center position of 1500 (+/-8).
5.2 Gyro / accelerometer angle check

After the receiver check is completed send the letter 'a' to start the angle check.

Don't move the quadcopter because the gyro needs to calibrate itself. After the calibration the roll and pitch angles are shown. The yaw value is the output of the gyro and will go back to zero if the yaw rotation stops.

Check if the angles correspond with the movement of the quadcopter:

    Nose up is positive pitch and nose down is negative pitch.
    Left wing up is positive roll and left wing down is negative roll.
    Nose right is positive yaw and nose left is negative yaw.
......


---------------------------------------------------
