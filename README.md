# 1.2p-SOS
void setup() {
  // initialize digital pin LED_BUILTIN as an output.
  pinMode(LED_BUILTIN, OUTPUT);
}

void loop() {
  digitalWrite (LED_BUILTIN, HIGH) ;  //turn the LED on (HIGH is the voltage level)
  delay(100);                     // wait for 0.1 second
  digitalWrite (LED_BUILTIN, LOW) ;   //turn the LED off by making the voltage LOW
  delay(1000);                        //wait for a second
  digitalWrite (LED_BUILTIN, HIGH) ;  //turn the LED on (HIGH is the voltage level)
  delay(100);                        // wait for 0.1 second
  digitalWrite (LED_BUILTIN, LOW) ;   //turn the LED off by making the voltage LOW
  delay(1000);                       //wait for a second
  digitalWrite (LED_BUILTIN, HIGH) ;  //turn the LED on (HIGH is the voltage level)
  delay(100);                       // wait for 0.1 second
  digitalWrite (LED_BUILTIN, LOW);    //turn the LED off by making the voltage LOW
  delay(1000);                        //wait for a second

  digitalWrite  (LED_BUILTIN, HIGH);  //turn the LED in (HIGH is the voltage level)
  delay(500);                    //wait for hald second
  digitalWrite (LED_BUILTIN, LOW);   //turn the LED off by making the voltage LOW
  delay(1000);                       //wait for a second
  digitalWrite  (LED_BUILTIN, HIGH); //turn the LED in (HIGH is the voltage level)
  delay(500);                   //wait for half a second
  digitalWrite (LED_BUILTIN, LOW);   //turn the LED off by making the voltage LOW
  delay(1000);                      // wait for a second
  digitalWrite  (LED_BUILTIN, HIGH); //turn the LED in (HIGH is the voltage level)
  delay(500);                     //wait for half second
  digitalWrite (LED_BUILTIN, LOW);   //turn the LED off by making the voltage LOW
  delay(1000);                       //wait for a second

  digitalWrite (LED_BUILTIN, HIGH) ;  //turn the LED on (HIGH is the voltage level)
  delay(100);                 // wait for 0.1 second
  digitalWrite (LED_BUILTIN, LOW) ;   //turn the LED off by making the voltage LOW
  delay(1000);                        //wait for a second
  digitalWrite (LED_BUILTIN, HIGH) ;  //turn the LED on (HIGH is the voltage level)
  delay(100);                         // wait for 0.1 second
  digitalWrite (LED_BUILTIN, LOW) ;   //turn the LED off by making the voltage LOW
  delay(1000);                       //wait for a second
  digitalWrite (LED_BUILTIN, HIGH) ;  //turn the LED on (HIGH is the voltage level)
  delay(100);                        // wait for 0.1 second
  digitalWrite (LED_BUILTIN, LOW);    //turn the LED off by making the voltage LOW
  delay(1000);                        //wait for a second

while(1) { /*empty*/ }
}
