# Work-on-Arduino-
keeping distance from the wall 

 int led = 13;
 int led2 = 7;
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(led, OUTPUT);
}

// the loop function runs over and over again forever
void loop() {
  digitalWrite(led2,LOW);
  delay(5000);
  digitalWrite(led2, HIGH);
  delay(5000);
  digitalWrite(led, LOW);   // turn the LED on (HIGH is the voltage level)
  delay(200);                       // wait for a second
  digitalWrite(led, HIGH);    // turn the LED off by making the voltage LOW
  delay(50);                       // wait for a second
}
