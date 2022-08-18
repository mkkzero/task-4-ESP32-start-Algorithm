# task-4-ESP32-start-Algorithm

Getting Started with the ESP32 Algorithm 


In this project, I program the ESP32 with Arduino IDE.

1-install SP32 Board in Arduino IDE.
2-decide the pins and set it in the code.
3-Upload Code to the ESP32.
4-controlling an LED connected to GPIO 23.
5-check if the LED connected to GPIO 23 is blinking.

//the code 

/*
  Blink
*/

// ledPin refers to ESP32 GPIO 23
const int ledPin = 23;

// the setup function runs once when you press reset or power the board
void setup() {
  // initialize digital pin ledPin as an output.
  pinMode(ledPin, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(ledPin, HIGH);   // turn the LED on (HIGH is the voltage level)
  delay(1000);                  // wait for a second
  digitalWrite(ledPin, LOW);    // turn the LED off by making the voltage LOW
  delay(1000);                  // wait for a second
}

made by Mohanad Ghurab for the summer training for the IOT task in smart methods
