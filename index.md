# Mini Tank Robot
The Mini Tank Robot is a controllable Robot Tank with treads and an ultrasonic sensor to detect distance. It is built with a controller to move the robot around. The biggest challenge I faced was soldering, because after attaching the wires, some would fall off and I would have to resolder them, and I also burnt my thumb when I touched the soldering pen.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Owen Z | Crystal Springs Uplands School | Civil/Mechanical Engineering | Incoming Freshman
<!-- -->
<img src="Owen Headshot.png" width="400" height="500"> <img src="Project Photo.png" width="400" height="400">

# Modification Milestone
<!--<iframe width="560" height="315" src="https://www.youtube.com/embed/IZsvjLhnbuk" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>-->

### Summary
For my modifications, I added boxes around the wiring of my robot and the controller, to make it more clean and not have wires sprouting all over the place. For the robot, it is a big box around the wiring, with holes for the batteries to connect to the Arduino, as well as the USB hole in case new code is added or a USB cable is needed in any way. For the remote control, the box is over the board that contains the Arduino and the bluetooth device, with a hole for the battery to connect to the Arduino to power the remote.

### Challenges
Some challenges I had were probably navigating the app, as it was sort of confusing on how to move things around and how to get them to be the right sizes. Another challenge was measuring the distance of objects, as it was pretty difficult to get precise mesurements and put them into the app, but in the end, I just made the sizes slightly bigger just in case.

# 3D Printed Items
### Box For Robot Wiring
<img src="Robot Wire Box Drawing.png" width="400" height="400"><img src="Robot Wire Box Pic.png" width="400" height="400">


### Box For Remote Controller
<img src = "Remote Controller Box Drawing.png" width="400" height="400"><img src = "Remote Controller Box.png" width="400" height="400">

# Final Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/P6zLDerVmH4" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Summary
My final milestone for the Mini Tank Robot was coding for and building the remote controller by soldering all of the parts together and naming it "Bobert". The buttons all correspond to the different movements, so forward, backward, left, and right respectively. The button board (the one with the buttons) and the bluetooth/arduino board were glued together to make it more hand held, and make it smaller and more like a controller. The forward button was melted a little, but it still works. Because the added USB battery is too large to fit on the remote itself, it would be recommended to carry it in a pocket.

### Challenges
Some challenges I had were coding the remote, as there were lots of errors and debugging to do, like getting the bluetooth modules to connect with eachother, and why the robot was randomly moving, and why buttons were randomly held down for extended periods of time. One of the main problem for the button pressing error was because of a print line that was not supposed to be there. Another challenge was soldering, as I kind of melted my thumb which hindered my progress a little bit. However, it didn't set me back by much, and I was able to finish it somewhat quickly. One more challenge was de-soldering, as I accidently put the resistors into the 5v line instead of the ground line, and de-soldering took forever, but I eventually got the hang of it. One final challenge I had was that sometimes the copper would rip off and I would have to solder the wires together or add more solder to replace the copper, which was difficult, as the solder wouldn't snap on to the place where the copper was.

### What I learned
At Bluestamp Engineering, I have learned how to make a circuit using breadboards, and how to solder materials like jumper wires and Arduinos onto perf boards. I also learned how ultrasonic sensors worked, and how all of the controller materials worked, like the Arduino, the L298N DC Motor Driver, and the hc-05 bluetooth modules. Another thing I learned here at Bluestamp was coding in c++. In the future, I want to learn more about how useful CAD is, and better ways to use it.

## Materials and Usage

### hc-05 Bluetooth Modules
<img src="Bluetooth Pic.png" width="400" height="200">
The bluetooth modules can be paired up together by going through AT mode and connecting them(Refrence AT mode code down below to connect them). Once connected, the bluetooth modules will blink rapidly twice. The bluetooth modules are also connected to seperate Arduinos, and these bluetooth modules are able to communicate with each other; by sending data through one Arduino to the other one. One bluetooth module, can also be called the "master", will usually be the one sending commands and data to the other bluetooth module, the "slave". To turn off AT Mode, disconnect the EN pin, and reset the USB cable.

### Ultrasonic Sensor
<img src="Ultrasonic Sensor Pic.png" width="400" height="200">
The ultrasonic sensor can sense how far something is, by using something similar to echo location. The sensor shoots out sound waves from the "eye" on the left, or the circular device connected to the trig pin, and recieves the data back in the echo pin, or the pin connected to the circular device on the right side. The distance is then calculated from the time it sends out the sound and recieves it back. The vcc pin is connected to power(5v), and the gnd pin is connected to Ground.

### Push buttons
<img src="Buttons Pic.png" width="400" height="300">
These buttons have 4 little legs on the underside, and are connected from one side to another, so opposite sides are connected, but once the button is pushed, all 4 legs are connected. The push buttons are connected to pins on the Arduino, and if you look at the code below, will learn how the Arduino knows if a button is clicked, but in simple terms, when the button is pushed, the Arduino gets a High signal, as it is normally Low, meaning the button was pushed, and runs the command the button is supposed to do when pushed. 

### Arduino
<img src="Arduino uno Pic.png" width="400" height="200">
The Arduinos have a USB port on them, and when connected to a device, can have code uploaded into the Arduino. The Arduino is the main component of the robot, and all of the materials go in part with the Arduino. The bluetooth modules need to be connected to the Arduino and then have specific code uploaded to get them connected. The buttons are connected into the Arduino to tell the Arduino if a button is pressed or not pressed. The ultrasonic sensor also requires code that is run from the Arduino to the sensor.

<!-- replace the [box parenthesis] with text that actually fit in

 **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.**

<iframe width="560" height="315" src="https://www.youtube.com/embed/F7M7imOVGug" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>


For your final milestone, explain the outcome of your project. Key details to include are:
- What you've accomplished since your previous milestone
- What your biggest challenges and triumphs were at BSE
- A summary of key topics you learned about
- What you hope to learn in the future after everything you've learned at BSE -->


# Second Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/mvPApYLQZsA" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Summary
My second milestone for the Mini Tank Robot was to code movement into the robot, as well as coding the ultrasonic sensors to work. The movement code is pretty easy, as all that was used was defining the functions such as "MoveForward" and "MoveBackward", and the way the functions are defined are setting the motor connections to either high or low. The ultrasonic sensor is coded to tell how far away something is, and move away if an obstacle is within the move away range. The movement was coded first, and then the ultrasonic sensor. Finally, I had to put the two codes together, by sensing the distance and then adding code from the movement to move away, such as stopping when the object is within the move away range, and turning to find another path.

### Challenges
I think one major challenge for me was getting started, as the codes on the internet didn't work with my robot, as most of the codes were for robots with 4 wheels and 4 motors, and not treads with 2 motors. The added difficulty was also probably due to the fact I haven't used C++ before in coding. Another challenge was probably putting the two codes together. It was a little tricky as I had to implement the movement code into the ultrasonic sensor so it can move away if needed. It also took a while for debugging, and then some more trial and error in getting the robot to turn a specific degree, as well as adding a stop function so the robot will stop for a bit, if an object is in the range where the robot will move around it.


<!-- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** 

<iframe width="560" height="315" src="https://www.youtube.com/embed/y3VAmNlER5Y" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

For your second milestone, explain what you've worked on since your previous milestone. You can highlight:
- Technical details of what you've accomplished and how they contribute to the final goal
- What has been surprising about the project so far
- Previous challenges you faced that you overcame
- What needs to be completed before your final milestone -->

# First Milestone
<iframe width="560" height="315" src="https://www.youtube.com/embed/-NY4l7gzPFc" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe> 

### Summary
My first milestone for the Mini Tank Robot was to build the body of the robot, so the wheels and the motors, as well as attatching many items to the robot, like the Arduino, the breadboard, and the motor driver. I also was able to have a temprary home for all of the wires and bluetooth devices on the bread board, as they will probably be finalized later. I was able to test the ultrasonic sensors to sense distance and the motors to see if they worked.

### Components Used
- 1 ultrasonic sensor
- 2 DC motors
- 2 treads
- 4 wheels
- 1 Arduino UNO microcontroller
- 1 Arduino Nano microcontroller
- 1 L298N Motor Driver
- 2 hc-05 bluetooth modules
- 1 9V battery
- 1 Half Breadboard
- 2 (half?) perf boards
- 4 Push Buttons
- Lots of jumper wires

I had to assemble the treads and wheels and the body together with a scrappy manual, but I got it done. The 2 DC motors are attatched to the wheels under the body, and same with the L298N Motor Driver, ziptied underneath the body. The Arduino microcontroller is placed on the middle of the body, and the half breadboard is on top of the motors on the upperside of the body. The 9v battery is placed on a cleared spot on top of the breadboard, and the ultrasonic sensor is hot glued onto the front of the robot (Above the L298N).

### Challenges Faced
Some challenges I faced was probably getting started. The manual for making the main body of the tank was pretty vauge and badly translated, and the images were poorly taken. Another challenge was attatching all of the extra items, such as the Arduino and L298N DC Motor Driver, as there was no guide, and the body of the tank was pretty small. In the end, I just taped most of them onto the top of the body, while I zip tied the L298N Motor Driver to the underside of the body. Another challenge I faced was probably attatching the wires, however, it wasn't neccesarily hard, just tedious.


<!-- **Don't forget to replace the text below with the embedding for your milestone video. Go to Youtube, click Share -> Embed, and copy and paste the code to replace what's below.** 

<iframe width="560" height="315" src="https://www.youtube.com/embed/CaCazFBhYKs" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

 For your first milestone, describe what your project is and how you plan to build it. You can include:
- An explanation about the different components of your project and how they will all integrate together
- Technical progress you've made so far
- Challenges you're facing and solving in your future milestones
- What your plan is to complete your project -->

# Schematics

### Main Robot Schematic
<img src="Robot Schematics.png" width="500" height="550">

## Robot Controller Schematic
<img src="Remote Control Schematics.png" width="600" height="250">

<!-- Here's where you'll put images of your schematics. [Tinkercad](https://www.tinkercad.com/blog/official-guide-to-tinkercad-circuits) and [Fritzing](https://fritzing.org/learning/) are both great resoruces to create professional schematic diagrams, though BSE recommends Tinkercad becuase it can be done easily and for free in the browser. -->

# Code

### Ultrasonic Sensors and Movement Code
```
#include <SoftwareSerial.h>

int trigPin = 12;    // Trigger
int echoPin = 13;    // Echo
long duration, cm, inches;

// Motor A connections
int in1 = 8;
int in2 = 7;
// Motor B connections
int in3 = 5;
int in4 = 4;

// The next part Tells which motors to move for the specific direction of movement
void MoveForward() {
	digitalWrite(in1, LOW);
	digitalWrite(in2, HIGH);
	digitalWrite(in3, HIGH);
	digitalWrite(in4, LOW);
}
 void MoveBackward() {
	digitalWrite(in1, HIGH);
	digitalWrite(in2, LOW);
	digitalWrite(in3, LOW);
	digitalWrite(in4, HIGH);	
 }

 void TurnRight() {
	digitalWrite(in1, HIGH);
	digitalWrite(in2, LOW);
	digitalWrite(in3, HIGH);
	digitalWrite(in4, LOW);
 }

 void TurnLeft() {
	digitalWrite(in1, LOW);
	digitalWrite(in2, HIGH);
	digitalWrite(in3, LOW);
	digitalWrite(in4, HIGH);
 }

 void Stop()	{
	digitalWrite(in1, LOW);
	digitalWrite(in2, LOW);
	digitalWrite(in3, LOW);
	digitalWrite(in4, LOW);
 }

 void setup() {
	Serial.begin (9600);

  //Define inputs and outputs
  pinMode(trigPin, OUTPUT);
  pinMode(echoPin, INPUT);

 	pinMode(in1, OUTPUT);
 	pinMode(in2, OUTPUT);
 	pinMode(in3, OUTPUT);
 	pinMode(in4, OUTPUT);
	
 	// Turn off motors - Initial state
 	digitalWrite(in1, LOW);
 	digitalWrite(in2, LOW);
 	digitalWrite(in3, LOW);
 	digitalWrite(in4, LOW);
 }

// This is the Ultrasonic sensor code
int MeasureDistance() {
  // The sensor is triggered by a HIGH pulse of 10 or more microseconds.
  // Give a short LOW pulse beforehand to ensure a clean HIGH pulse:
  digitalWrite(trigPin, LOW);
  delayMicroseconds(5);
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin, LOW);

  // Read the signal from the sensor: a HIGH pulse whose
  // duration is the time (in microseconds) from the sending
  // of the ping to the reception of its echo off of an object.
  pinMode(echoPin, INPUT);
  duration = pulseIn(echoPin, HIGH);
 
  // Convert the time into a distance
  cm = (duration/2) / 29.1;     // Divide by 29.1 or multiply by 0.0343
  inches = (duration/2) / 74;   // Divide by 74 or multiply by 0.0135
	return(inches);
	
 }
// Puts the movement and ultrasonic sensor codes together
void loop() {
 int Distance = MeasureDistance();
	//Serial.println(Distance);
	if(Distance <= 5) {
	Stop();
	delay(750);
	TurnRight();
	delay(610);	// Turns the robot approximately 90 degrees
	}
	else {
	MoveForward();
	delay(1000);
	}
}
```

### Remote Controller Code
```
#include <SoftwareSerial.h>
// Make sure the TX and RX pins match
SoftwareSerial BTSerial(10, 11);   // TX | RX
bool FORWARD = false;
bool BACKWARD = false;
bool LEFT = false;
bool RIGHT = false;

int Command;

int FORWARDPRESS = 1;
int FORWARDRELEASE = 2;
int BACKWARDPRESS = 3;
int BACKWARDRELEASE = 4;
int LEFTPRESS = 5;
int LEFTRELEASE = 6;
int RIGHTPRESS = 7;
int RIGHTRELEASE = 8;

const int buttonPin2 = 2; 
const int buttonPin3 = 3; 
const int buttonPin4 = 4; 
const int buttonPin5 = 5; 

void setup()  {
  Serial.begin(9600);
  // Serial.println("Enter AT commands:");
  BTSerial.begin(38400);       // HC-05 default speed in AT command more

  pinMode(buttonPin2, INPUT);
  pinMode(buttonPin3, INPUT);
  pinMode(buttonPin4, INPUT);
  pinMode(buttonPin5, INPUT);
}


// variables will change:
int buttonState = 0;  // variable for reading the pushbutton status

	// Reads button state to determine if the button is pressed or not
void loop() {
  // read the state of the pushbutton value:
  buttonState = digitalRead(buttonPin2);
  FORWARD = buttonState == HIGH;
  // Serial.println(FORWARD);
  buttonState = digitalRead(buttonPin3);
  BACKWARD = buttonState == HIGH;
  // Serial.println(BACKWARD);
  buttonState = digitalRead(buttonPin4);
  LEFT = buttonState == HIGH;
  // Serial.println(RIGHT);
  buttonState = digitalRead(buttonPin5);
  RIGHT = buttonState == HIGH;
  // Serial.println(LEFT);

	// Sends the integer values to to the bluetooth device connected to the Robot's Arduino
  if (LEFT) {
    BTSerial.write(LEFTPRESS);
  }
  else  {
    BTSerial.write(LEFTRELEASE);
  }
  if (RIGHT) {
    BTSerial.write(RIGHTPRESS);
  }
  else  {
    BTSerial.write(RIGHTRELEASE);
  }

  if (FORWARD) {
    BTSerial.write(FORWARDPRESS);
  }
  else  {
    BTSerial.write(FORWARDRELEASE);
  }

  if (BACKWARD) {
    BTSerial.write(BACKWARDPRESS);
  }
  else  {
    BTSerial.write(BACKWARDRELEASE);
  }
 BTSerial.flush();
 delay(50);
}
```

### Robot Controller Code
```
#include <SoftwareSerial.h>

// Motor A connections
int in1 = 8;
int in2 = 7;
// Motor B connections
int in3 = 5;
int in4 = 4;

void MoveForward() {
	digitalWrite(in1, LOW);
	digitalWrite(in2, HIGH);
	digitalWrite(in3, HIGH);
	digitalWrite(in4, LOW);
}
 void MoveBackward() {
	digitalWrite(in1, HIGH);
	digitalWrite(in2, LOW);
	digitalWrite(in3, LOW);
	digitalWrite(in4, HIGH);	
 }

 void TurnRight() {
	digitalWrite(in1, HIGH);
	digitalWrite(in2, LOW);
	digitalWrite(in3, HIGH);
	digitalWrite(in4, LOW);
 }

 void TurnLeft() {
	digitalWrite(in1, LOW);
	digitalWrite(in2, HIGH);
	digitalWrite(in3, LOW);
	digitalWrite(in4, HIGH);
 }

 void Stop()	{
	digitalWrite(in1, LOW);
	digitalWrite(in2, LOW);
	digitalWrite(in3, LOW);
	digitalWrite(in4, LOW);
 }

SoftwareSerial BTSerial(9, 11);   //RX | TX
bool FORWARD = false;
bool BACKWARD = false;
bool LEFT = false;
bool RIGHT = false;

int Command;

int FORWARDPRESS = 1;
int FORWARDRELEASE = 2;
int BACKWARDPRESS = 3;
int BACKWARDRELEASE = 4;
int LEFTPRESS = 5;
int LEFTRELEASE = 6;
int RIGHTPRESS = 7;
int RIGHTRELEASE = 8;

const int buttonPin2 = 2; 
const int buttonPin3 = 3; 
const int buttonPin4 = 4; 
const int buttonPin5 = 5; 


void setup()  {
  Serial.begin(9600);
  // Serial.println("Enter AT commands:");
  BTSerial.begin(38400);       // HC-05 default speed in AT command more
  BTSerial.listen();
}

	// Determines which buttons are true to determine which direction the robot moves
void loop() {
  if (FORWARD && !BACKWARD && !RIGHT && !LEFT)  {
   MoveForward();
 }
   else if (!FORWARD && BACKWARD && !RIGHT && !LEFT) {
  //  Serial.println("Moving Backward");
   MoveBackward();
   }
   else if (!FORWARD && !BACKWARD && RIGHT && !LEFT) {
    //  Serial.println("Turning Right");
     TurnRight();
   }
   else if (!FORWARD && !BACKWARD && !RIGHT && LEFT)  {
    //  Serial.println("Turning Left");
     TurnLeft();
   }
   else {
     Stop();
   }

  if (BTSerial.available() == 0)  {
   return;
  }
	// Reads what integer value is being sent from the Remote Controller bluetooth device
int command = BTSerial.read();
  if (command == 1) {
		FORWARD = true;
		}
    else if (command == 2) {
      FORWARD = false;
    }
  if (command == 3) {
      BACKWARD = true;
    }
    else if (command == 4) {
      BACKWARD = false;
    }
  if (command == 7) {
      RIGHT = true;
    }
    else if (command == 8) {
      RIGHT = false;
    }
  if (command == 5) {
      LEFT = true;
    }
    else if (command == 6) {
      LEFT = false;
    }
}
```

### Button Code
```
const int buttonPin2 = 2; 
const int buttonPin3 = 3; 
const int buttonPin4 = 4; 
const int buttonPin5 = 5; 

int buttonState = 0;  // variable for reading the pushbutton status

void setup() {
  	// initialize the pushbutton pin as an input:
  pinMode(buttonPin2, INPUT);
  pinMode(buttonPin3, INPUT);
  pinMode(buttonPin4, INPUT);
  pinMode(buttonPin5, INPUT);
}

void loop() {
  	// Read the state of the pushbutton
	// If the pushbutton is HIGH, sets the direction corresponding to the button to true
  buttonState = digitalRead(buttonPin2);
  LEFT = buttonState == HIGH;
  buttonState = digitalRead(buttonPin3);
  FORWARD = buttonState == HIGH;
  buttonState = digitalRead(buttonPin4);
  BACKWARD = buttonState == HIGH;
  buttonState = digitalRead(buttonPin5);
  RIGHT = buttonState == HIGH;

}
```

### AT Mode Code(Connecting two bluetooth modules together)
```
#include <SoftwareSerial.h>
//SoftwareSerial BTSerial(5, 6); // RX | TX	What pins the RX and TX pins on the bluetooth module are connected to on the Arduino
SoftwareSerial BTSerial(10, 11);   // RX | TX
void setup()
{
  Serial.begin(9600);
  Serial.println("Enter AT commands:");
  BTSerial.begin(38400);       // HC-05 default speed in AT command more
}
void loop()
{
  if (BTSerial.available())    // read from HC-05 and send to Arduino Serial Monitor
  Serial.write(BTSerial.read());
  if (Serial.available())     // Keep reading from Arduino Serial Monitor and send to HC-05
  BTSerial.write(Serial.read());
}
// To set them to be connected, enter AT+UART=1 on the "master" bluetooth module, and enter AT+UART=0 on the "slave" bluetooth module
// Remember to put the EN pin into the 3.3v, and it will be in AT mode if the led on the module is blinking slowly.
```

# Bill of Materials

<!--Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->


| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| hc-sr04 Ultrasonic sensor | Detect how far away items are | $11.00 | <a href="https://www.radwell.com/Buy/SAINSMART/SAINSMART/HC-SR04?source=GoogleShopping&IgnoreRedirect=true&ItemSingleId=49511201&viewAll=true&adlclid=87f76da74f751e990a7c05fd858c4998&msclkid=87f76da74f751e990a7c05fd858c4998&utm_source=bing&utm_medium=cpc&utm_campaign=%5BLegacy%5D%20%5BPLA%5D%20SC%20Shopping%20-%20In%20Stock%20-%20Generic%20-%20Bing&utm_term=4580909046059686&utm_content=SC%20-%20In%20Stock%20-%20Generic/"> Link </a> |
| 2WD Tank Robot Chassis Platform | Main body of robot | $20.99 | <a href="https://www.amazon.com/Intelligent-Compatible-Bluetooth-Scientific-Competition/dp/B09VZVFL9D/ref=sr_1_4_sspa?crid=2NOX1B9B43L9G&dib=eyJ2IjoiMSJ9.5Xkf7i82-ZX_TZVpc-T3hgmVSTjtvvPnonn3ELuJ2_5IXtit_ijHc6-whElHUJ1nHYRUJ3NyMjlbjHoATZEdT3LodlRtztMcDrw6A1OF0czFP_aG8kW85m2rwD4hiz_iZsWn7hdChdSlNaN1QJTww4GIkn9M8-ZVYps6OOQ3zqwjJVvrwJva_0xYzq9APIcJQL12EiviRQTcr5kk9kp5qeTMPyJVdHqV-2rl70GGGawFUHxinyG_542Zy0BwYOIVmT-lVy26Vcg3-mQWpygCcAToXzrlA1nJFwZRviSgHAA.EegzuEWuR8ryWxOzRaqQzta-bthNVX_mLG0vaO6uvAQ&dib_tag=se&keywords=tank+robot+chassis&qid=1750957125&sprefix=tank+robot+chassis%2Caps%2C165&sr=8-4-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1/"> Link </a> |
| Arduino Uno R3| Contains the code for movement | $27.99 | <a href="https://www.walmart.com/ip/Arduino-Uno-Rev-3-Uno-R3-A000066/182664904?intsrc=CATF_9768&clickid=TSnzBe1WKxycTBIzdBV78Wj9UksXXWT4Q2Dk1M0&irgwc=1&sourceid=imp_TSnzBe1WKxycTBIzdBV78Wj9UksXXWT4Q2Dk1M0&veh=aff&wmlspartner=imp_27795&affiliates_ad_id=612734&campaign_id=9383&sharedid=6080654/"> Link </a> |
| Arduino Nano 3.0 | Contains the code for the remote | $24.75 | <a href="https://www.amazon.com/dp/B003YVL34O?&tag=usdeexplicits-20/"> Link </a> |
| L298N Motor Driver | Controls the DC Motors | $8.99 | <a href="https://www.amazon.com/Qunqi-Controller-Module-Stepper-Arduino/dp/B014KMHSW6/ref=sr_1_56?crid=2PXGS09EQWDRY&dib=eyJ2IjoiMSJ9.qawDn99TGs75N0slRxye4NsZmm8TPWyznPap_7RkjFdmPwBiu8gx-3hRNvV-zfTWtBJBeSLVCwXihOIE04jygL7pBm-Ek0idYs1YsAlKCfo.iM7rFy3oaCdNFqcC58Z5uXyjvNFD_EGVyWP9b9ZLaFA&dib_tag=se&keywords=single+l298n+motor+driver&qid=1750957714&sprefix=singlel298n+motor+driver%2Caps%2C174&sr=8-56&xpid=kqIxH__xzJ50_/"> Link </a> |
| 2 hc-05 Bluetooth Modules | Connects the robot with its controller | $3.99 | <a href="https://www.walmart.com/ip/HC-05-Wireless-Bluetooth-RF-Transceiver-Module-serial-RS232-TTL-For-New-L3W9/1488123570?clickid=TSnzBe1WKxycTBIzdBV78Wj9UksSFJTkQ2Dk1M0&irgwc=1&sourceid=imp_TSnzBe1WKxycTBIzdBV78Wj9UksSFJTkQ2Dk1M0&veh=aff&wmlspartner=imp_3682317&affiliates_ad_id=1285387&campaign_id=9383&sharedid=/"> Link </a> |
| (Optional) USB Battery with micro usbc end | Power the remote | $14.99 | <a href="https://www.ebay.com/itm/336007350940?chn=ps&norover=1&mkevt=1&mkrid=711-167538-502585-0&mkcid=2&mkscid=101&itemid=336007350940&targetid=4580290580353178&device=c&mktype=&googleloc=43952&poi=&campaignid=605356526&mkgroupid=1227056077612866&rlsatarget=pla-4580290580353178&abcId=10247775&merchantid=51291&msclkid=b2a490d3f9b711c01ba2f8a5805ddd36"> Link </a> |



# Resources
- https://lastminuteengineers.com/l298n-dc-stepper-driver-arduino-tutorial/
- https://randomnerdtutorials.com/complete-guide-for-ultrasonic-sensor-hc-sr04/
- https://www.instructables.com/How-to-Set-AT-Command-Mode-for-HC-05-Bluetooth-Mod/
- https://app.cirkitdesigner.com/

<!-- One of the best parts about Github is that you can view how other people set up their own work. Here are some past BSE portfolios that are awesome examples. You can view how they set up their portfolio, and you can view their index.md files to understand how they implemented different portfolio components. --!>


<!-- [Example 1](https://trashytuber.github.io/YimingJiaBlueStamp/) -->
<!-- [Example 2](https://sviatil0.github.io/Sviatoslav_BSE/) -->
<!-- [Example 3](https://arneshkumar.github.io/arneshbluestamp/) -->

<!--- To watch the BSE tutorial on how to create a portfolio, click here. -->

# Starter Project - Retro Arcade Console
<iframe width="560" height="315" src="https://www.youtube.com/embed/GMSt7f6rHI0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

### Summary
My starter project was the Retro Arcade Console. The Retro Arcade Console has 5 games in retro style. It has 4 buttons on the front that control movement of the games, and with the two buttons on the side, the one on top controls which game you want to play and the settings, while the one on the bottom can pause/unpause the games. The red button is the on/off button.

### Challenges Faced
Some challenges I faced were definitley soldering. I soldered the USB port upside down, and it was a struggle taking it off. In the end, we had to sort of wedge it off, rendering the USB port useless, however I was lucky that the USB port was not an important aspect of the Retro Arcade Console, as it is really only used for changing the code. Another challenge involving soldering is that sometimes, my soldering iron would not melt the solder, making soldering incredibily difficult.
