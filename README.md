# Electronics_project_robot_eyes
Using LED to control the eyes of a robot.
### **Component List:**
1. Arduino Uno R3
2. Breadboard
3. PNP Transistor (BJT)
4. LED
5. Resistor
![Robot eyes](https://user-images.githubusercontent.com/88051753/128227652-26622ff1-38e7-46d9-8f86-1d593b5d0c21.png)

### **Steps:**
1. Connect power and ground to the circuit
2. Connect power to the Anode of the LED, and connect the cathode of LED with the resistor.
3. Connect terminal 2 of the resistor with the emitter of the transistor.
4. Connect the bases of the transistor with digital pins(2 & 3).
5. Connect the collector of the transistor with the ground.
### **Code:**
`int D2 = 2 ;
int D3 = 3 ;

void setup() { 
  
pinMode(2, OUTPUT);
pinMode(3, OUTPUT);
}

void loop() {

digitalWrite(2, HIGH);
delay(15);

digitalWrite(2, LOW);
delay(15); 
  
digitalWrite(3, HIGH);
delay(15); 
  
digitalWrite(3, LOW);
delay(15); 
}`
### **Simulation:**
https://www.tinkercad.com/things/cSsMeoix97f-super-lappi-curcan/editel?sharecode=6qLeJirloPWFbmpsmK3QKVZYMUTL7dBYY-LU4LKgQPw 
