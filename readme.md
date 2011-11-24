

ARRANGEMENTS:
the circuit works in the following manner.
1. patch up  the components. the components values are mentioned in the 'Bill of Material' file.
2. attach motor terminals to the motor connector.
3. attach two switches at the Start and Reset connectors.
4. attach the wires from the  limit switch to the jumper JP1, in such a way that the 'NC'( normally closed pin) is attached to pin 3 of JP1. the 'NO'(normally one pin) attached to the pin 1 of JP1 and the 'C'(common) is attached to the pin 2 of JP1. the limit switch is added for safety so that when reset is pressed, the motor does not runs in the reverse direction after it has reached its initial state. if you dont want to use the limit switch,please SHORT the pin 2 and 3 of the JP1.
5. connect a 12volt battery to the battery connector.

the circuit will turn on when the battery gets connected. to start the motor, push the ' start' button once. it will move for ~4secs and then stop. it will continue to do the same process. to bring the motor back to the initial state press the 'reset' button. it will make the motor to move in reverse direction for a longer period of time (~1-2mins which can be adjusted upto 10-20minutes by changing the values of resistors and capacitors). the motor will stop after that time or the limit switch is pressed, ready for the next input.


ADJUSTMENTS:
the time durations for the motor to run can be adjusted. to adjust the duration to move the motor in the forward direction( for forcing the fragrance out). turn the screw of variable resistor RV1. although it is adjusted to nearly 4 seconds but it can be fine tuned by adjusting RV1 according to the requirements.

to adjust the duration of motor in reverse drection ( when reset is pressed) the adjustments can be made in two ways. 1: small adjustments can be made by turning the screw of VR2. 2: for larger variations we can change the resistor R5 or the capacitor C8. the formula for the time duration is T=1.1 x R x C. greater the R and C, longer will be the duration. you may ask me to calculate the components values for the desired results.

PRECAUTIONS:
1. the IC U1 will get hot if the motor draws two much current. the IC can handle motors with current ratings of 2Amperes and 12 Volts.
2.  if the motor gets stuck and the circuit is forcing it to move, it may damage the circuit. try to remove any blockage by hand.
3. be careful while connecting the limit switch and make sure appropriate pins are connected as mentioned above. you may learn about limit switches from wikipedia before using them.
