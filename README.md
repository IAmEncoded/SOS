# SOS
int o = 1000;
int s = 500;
int del = 1500;
void setup() {
pinMode(5, OUTPUT);
}
void loop() {
digitalWrite(5, HIGH);
delay(s);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(s);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(s);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(o);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(o);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(o);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(s);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(s);
digitalWrite(5, LOW);
delay(500);
digitalWrite(5, HIGH);
delay(s);
digitalWrite(5, LOW);
delay(del);
}
