# Password-Lock
This is an embedded system project that checks whether the entered password is correct or not and displays the output (Correct / Error) on LCD.

Hardware components used:
1. MT8870 DTMF
2. Atmega16A microcontroller
3. LCD
4. Microphone
5. Push button
6. Various resistors and capacitors

Operation:
1. Programming Mode:
- Press on the push button and hold for 2 seconds to enter the prgramming mode.
- Enter the password to be stored on ROM using a Dial tone mobile app (keep pressing the button while entering password)
- Once you leave the button, you exit the programming mode.

2. Normal Mode:
- User enters password using Dial tone mobile.
- The program keeps validating the user's input digit by digit and if an digit is wrong, it will dipslay 'Error' on LCD and clears the user's input.
- If the user enters a correct password, the LCD displays 'Success'.
