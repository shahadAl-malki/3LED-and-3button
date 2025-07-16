# 3LED-and-3button
void setup() {
  pinMode(13, OUTPUT); // الليد الأول
  
  pinMode(12, OUTPUT); // الليد الثاني
  
  pinMode(11, OUTPUT); // الليد الثالث
}

void loop() {
  digitalWrite(13, HIGH); // يشتغل الأول
  delay(500);
  digitalWrite(13, LOW);

  digitalWrite(12, HIGH); // يشتغل الثاني
  delay(500);
  digitalWrite(12, LOW);

  digitalWrite(11, HIGH); // يشتغل الثالث
  delay(500);
  digitalWrite(11, LOW);
}
