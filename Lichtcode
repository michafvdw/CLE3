//de "blanks" moeten vervangen worden door de pins die we gebruiken
int redPin1 = blank;        //rgb led 1
int greenPin1 = blank;
int bluePin1 = blank;
                   
int redPin2 = blank;        //rgb led 2
int greenPin2 = blank;
int bluePin2 = blank;

char Incoming_value = 0;

void setup() {
Serial.Begin(9600_;
  pinMode(redPin1, OUTPUT);
  pinMode(greenPin1, OUTPUT);
  pinMode(bluePin1, OUTPUT);
  pinMode(redPin2, OUTPUT);
  pinMode(greenPin2, OUTPUT);
  pinMode(bluePin2, OUTPUT);

}
void loop(){
  if(Serial.available() > 0)
  {
    Incoming_value = Serial.read();
    Serial.print(Incoming_value);
    Serial.print("\n")
    If(Incoming_value == '1')
    digitalWrite(blank, HIGH);
    else if(Incoming_value == '0')
      digitalWrite(blank, LOW);
  }
}
void Song1() {
  RGB_color1(255, 0, 0); // Red
  delay(1000);
  RGB_color1(0, 255, 0); // Green
  delay(1000);
  RGB_color1(0, 0, 255); // Blue
  delay(1000);
  RGB_color1(255, 255, 125); // Raspberry
  delay(1000);
  RGB_color1(0, 255, 255); // Cyan
  delay(1000);
  RGB_color1(255, 0, 255); // Magenta
  delay(1000);
  RGB_color1(255, 255, 0); // Yellow
  delay(1000);
  RGB_color1(255, 255, 255); // White
  delay(1000);
}
  void Song2() {
  RGB_color2(0, 255, 255); // Cyan
  delay(1000);
  RGB_color2(255, 0, 255); // Magenta
  delay(1000);
  RGB_color2(255, 255, 0); // Yellow
  delay(1000);
  RGB_color2(255, 255, 255); // White
  delay(1000);
  RGB_color2(255, 0, 0); // Red
  delay(1000);
  RGB_color2(0, 255, 0); // Green
  delay(1000);
  RGB_color2(0, 0, 255); // Blue
  delay(1000);
  RGB_color2(255, 255, 125); // Raspberry
  delay(1000);
   
}
void RGB_color1(int redValue1, int greenValue1, int blueValue1)
 {
  analogWrite(redPin1, redValue1);
  analogWrite(greenPin1, greenValue1);
  analogWrite(bluePin1, blueValue1);
}
void RGB_color2(int redValue2, int greenValue2, int blueValue2)
 {
  analogWrite(redPin2, redValue2);
  analogWrite(greenPin2, greenValue2);
  analogWrite(bluePin2, blueValue2);
}
