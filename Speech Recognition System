#include <SoftwareSerial.h>
SoftwareSerial BT(10, 11); // RX, TX
int devicePin = 8;

void setup() {
  pinMode(devicePin, OUTPUT);
  BT.begin(9600);
  Serial.begin(9600);
}

void loop() {
  if (BT.available()) {
    char cmd = BT.read();
    Serial.println(cmd);
    if (cmd == '1') digitalWrite(devicePin, HIGH); // Voice command "ON" = 1
    else if (cmd == '0') digitalWrite(devicePin, LOW); // Voice command "OFF" = 0
  }
}
