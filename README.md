# ClassroomSecuritySystem_DLD
Classroom Security System: Our system consists of two modules. One is a card reader, and the second is a keypad, as shown below.
<\br>
A student may enter the “M3” classroom using a particular door (door1 or door2) if he or she has a card containing the corresponding code and enters an authorised keypad code for that card. The outputs from the card reader are as follows:
<\br>
Description A B <\br>
No Card Inserted 0 0<\br>
Card Code (door1) 0 1<\br>
Card Code (door2) 1 1<\br>
Invalid Card Code 1 0<\br>

To unlock a door, a student must hold down the proper keys on the keypad and, then, insert the card in the reader. The authorised keypad codes for door 1 are even entry numbers, and the authorised keypad codes for door 2 are odd entry numbers. If the card has an invalid code or if the wrong keypad code is entered, the alarm will ring when the card is inserted. If the correct keypad code is entered, the corresponding door will be unlocked when the card is inserted.
<\br>
Keypad module: This converts a decimal digit to an appropriate code for selecting segments in an indicator used to display the decimal digit in a familiar form. The seven outputs of the decoder (p, q, r, s, t, u, v) select the corresponding segments in the display, as shown below. The numeric display chosen to represent the decimal digit is shown below. Design the decoder for our keypad module using a minimum number of gates.
