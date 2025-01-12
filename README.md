# Project-1-LED-Blinking-with-Arduino-
Blinking LED project. Turns on an LED on for one second,  then off for one second, repeatedly.



This is my first Arduino project. I'm so happy to do something new.

Components and supplies
-----------------------

*LED (generic)

*Jumper wires (generic)

*Arduino Uno

*Resistor 100 ohm



Apps and platforms
-------------------
Arduino IDE




Code
--------------
// the setup function runs once when you press reset or power the board

void setup() 

{
// initialize digital pin LED_BUILTIN as an output.

  pinMode(7, OUTPUT);
  
}

// the loop function runs over and over again forever
void loop() 
{
  digitalWrite(7, HIGH);  // turn the LED on (HIGH is the voltage level)
  
  delay(1000);                      // wait for a second
  
  digitalWrite(7, LOW);   // turn the LED off by making the voltage LOW
  
  delay(1000);                      // wait for a second
}

