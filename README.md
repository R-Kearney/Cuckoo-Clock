# Cuckoo-Clock
Arduino Controlled Cuckoo Clock

This project came about after my Nana's old Cuckoo Clock stopped working one day.

She missed the birds song and apperance every hour.

During my christmas Holidays I took it upon myself to fix the clock.


The electronics in the clock were very old and had no online datasheets.

I was unable to find the broken part so I decided it would be easier replace the old electronics with an Arduino Microcontroller.

The Arduino would connect to the Bird out Motor, Flap wings Solenoid, Speaker and LDR.

The Cuckoo sound was converted to 8-bit PCM to fit onto the Arduino's built in Memory.

Standard operation of the new electronics is:

1. If LDR indicates its Day & Hour contacts are pressed:
2. Activate motor to send the bird out
3. Play Cuckoo song
4. Flap wings
5. Play Cuckoo song
6. Bring the Bird back in
7. Delay for 33 minutes before being allow repeat
