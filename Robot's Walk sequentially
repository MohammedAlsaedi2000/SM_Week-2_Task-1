# SM_Week-2_Task-1
Arduino servo code to simulate Robot walk. But this one shows real movement just like as if the robot legs are walking.

The following code shows the sequence movement of each servo as if it is walking:
---------------------------------------------------------------------------------------------------------------------------------------
#include <Servo.h>

Servo servo_ankle1;
Servo servo_knee1;
Servo servo_thigh1;
Servo servo_ankle2;
Servo servo_knee2;
Servo servo_thigh2;

void setup() {
  servo_ankle1.attach(3);
  servo_knee1.attach(5);
  servo_thigh1.attach(6);
  servo_ankle2.attach(9);
  servo_knee2.attach(10);
  servo_thigh2.attach(11);  
  
  // Initialize all servos to 90 degrees
  servo_ankle1.write(90);
  servo_knee1.write(90);
  servo_thigh1.write(90);
  servo_ankle2.write(90);
  servo_knee2.write(90);
  servo_thigh2.write(90);
  delay(1000);  // Wait for servos to reach the initial position
}

void loop() {
  walk();
}

void walk() {
  // Step 1: Lift left leg
  servo_thigh1.write(120);
  delay(500);
  servo_knee1.write(60);
  delay(500);
  servo_ankle1.write(60);
  delay(500);

  // Step 2: Move left leg forward
  servo_thigh1.write(90);
  delay(500);
  servo_knee1.write(90);
  delay(500);
  servo_ankle1.write(90);
  delay(500);

  // Step 3: Lift right leg
  servo_thigh2.write(120);
  delay(500);
  servo_knee2.write(60);
  delay(500);
  servo_ankle2.write(60);
  delay(500);

  // Step 4: Move right leg forward
  servo_thigh2.write(90);
  delay(500);
  servo_knee2.write(90);
  delay(500);
  servo_ankle2.write(90);
  
  delay(500);
}


---------------------------------------------------------------------------------------------------------------------------------------


