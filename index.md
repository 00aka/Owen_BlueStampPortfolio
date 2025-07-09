# Mini Tank Robot
<!-- Replace this text with a brief description (2-3 sentences) of your project. This description should draw the reader in and make them interested in what you've built. You can include what the biggest challenges, takeaways, and triumphs from completing the project were. As you complete your portfolio, remember your audience is less familiar than you are with all that your project entails! -->


| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Owen Z | Crystal Springs Uplands School | Civil/Mechanical Engineering | Incoming Freshman

<!-- **Replace the BlueStamp logo below with an image of yourself and your completed project. Follow the guide [here](https://tomcam.github.io/least-github-pages/adding-images-github-pages-site.html) if you need help.**

![Headstone Image](logo.svg) -->

# Final Milestone

### Summary
My final milestone for the Mini Tank Robot was coding for and building the remote controller by soldering all of the parts together, naming it Bobert, and adding all of my modifications, like the '[add modification name]'. [ADD MORE STUFF]

### Challenges
Some challenges I had were coding the remote, as there were lots of errors and debugging to do, like getting the bluetooth modules to connect with eachother, and why the robot was randomly moving, and why buttons were randomly held down for extended periods of time. Overall, the coding was not entirely enjoyable, as the one main problem for the button pressing error was because of a print line. Another challenge was soldering, as I couldn't really figure out how to start, and I kind of melted my thumb which hindered my progress a little bit. However, once I knew how to start, the process kind of just progressed more smoothly without [hopefully] any more injuries. One more challenge was de-soldering, as I accidently put the resistors into the 5v instead of ground, and de-soldering took forever, but I eventually got the hang of it.

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
My second milestone for the Mini Tank Robot was to code movement into the robot, as well as coding the ultrasonic sensors to work. The movement code is pretty self explanable, but the ultrasonic sensor is coded to tell how far away something is, and move away if needed. The movement code was coded first, and was pretty simple, as all I had to do was define the directions and just test which combinations of the motors on high and low worked for the specific direction the robot moved. The ultrasonic sensor code was a little more tricky, as I had to get it to sense distance and then code the movement to make needed adjustments, with more trial and error.

### Challenges
I think one major challenge for me was getting started, as the codes on the internet didn't work with my robot, as most of the codes were for robots with 4 wheels and 4 motors, and not treads with 2 motors. The added difficulty was also probably due to the fact I haven't used C++ before in coding. Another challenge was probably getting the code to work. It took a while for debugging, and then some more trial and error in getting the robot to turn a specific degree, as well as adding a stop function so the robot will stop for a bit, if an object is in the range where the robot will move around it.


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
My first milestone for the Mini Tank Robot was to build the body of the robot, so the wheels and the motors, as well as attatching many items, like the Arduino, the breadboard, and the motor driver. I was also able to test the ultrasonic sensors and the motors to see if they work.

### Components Used
- 1 ultrasonic sensor
- 2 DC motors
- 2 treads
- 4 wheels
- 1 Arduino microcontroller
- 1 L298N Motor Driver
- 1 hc-05 bluetooth module
- 1 USB cable
- 1 9V battery
- 1 Half Breadboard

I had to assemble the treads and wheels and the body together with a scrappy manual, but I got it done. The 2 DC motors are attatched to the wheels under the body, and same with the L298N Motor Driver, ziptied underneath the body. The Arduino microcontroller is placed on the middle of the body, and the 9V battery is placed next to the audino. A half breadboard is used for the bluetooth module and the ultrasonic sensor. The ultrasonic sensor is placed on top of the battery, but taped on for an easy change of battery if needed. The USB cable is only needed to upload code from the computer to the Arduino.

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
<img src="Robot Schematics.png" width="600" height="600">

- Resistors are 10k
- Via CirkitDesigner
- Redo schematic because of new changes to the breadboard


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
# Bill of Materials

<!--Here's where you'll list the parts in your project. To add more rows, just copy and paste the example rows below.
Don't forget to place the link of where to buy each component inside the quotation marks in the corresponding row after href =. Follow the guide [here]([url](https://www.markdownguide.org/extended-syntax/)) to learn how to customize this to your project needs. -->


| **Part** | **Note** | **Price** | **Link** |
|:--:|:--:|:--:|:--:|
| hc-sr04 Ultrasonic sensor | Detect how far away items are | $11.00 | <a href="https://www.radwell.com/Buy/SAINSMART/SAINSMART/HC-SR04?source=GoogleShopping&IgnoreRedirect=true&ItemSingleId=49511201&viewAll=true&adlclid=87f76da74f751e990a7c05fd858c4998&msclkid=87f76da74f751e990a7c05fd858c4998&utm_source=bing&utm_medium=cpc&utm_campaign=%5BLegacy%5D%20%5BPLA%5D%20SC%20Shopping%20-%20In%20Stock%20-%20Generic%20-%20Bing&utm_term=4580909046059686&utm_content=SC%20-%20In%20Stock%20-%20Generic/"> Link </a> |
| 2WD Tank Robot Chassis Platform | Main body of robot | $20.99 | <a href="https://www.amazon.com/Intelligent-Compatible-Bluetooth-Scientific-Competition/dp/B09VZVFL9D/ref=sr_1_4_sspa?crid=2NOX1B9B43L9G&dib=eyJ2IjoiMSJ9.5Xkf7i82-ZX_TZVpc-T3hgmVSTjtvvPnonn3ELuJ2_5IXtit_ijHc6-whElHUJ1nHYRUJ3NyMjlbjHoATZEdT3LodlRtztMcDrw6A1OF0czFP_aG8kW85m2rwD4hiz_iZsWn7hdChdSlNaN1QJTww4GIkn9M8-ZVYps6OOQ3zqwjJVvrwJva_0xYzq9APIcJQL12EiviRQTcr5kk9kp5qeTMPyJVdHqV-2rl70GGGawFUHxinyG_542Zy0BwYOIVmT-lVy26Vcg3-mQWpygCcAToXzrlA1nJFwZRviSgHAA.EegzuEWuR8ryWxOzRaqQzta-bthNVX_mLG0vaO6uvAQ&dib_tag=se&keywords=tank+robot+chassis&qid=1750957125&sprefix=tank+robot+chassis%2Caps%2C165&sr=8-4-spons&sp_csd=d2lkZ2V0TmFtZT1zcF9hdGY&psc=1/"> Link </a> |
| Arduino Uno R3| Arduino | $27.99 | <a href="https://www.walmart.com/ip/Arduino-Uno-Rev-3-Uno-R3-A000066/182664904?intsrc=CATF_9768&clickid=TSnzBe1WKxycTBIzdBV78Wj9UksXXWT4Q2Dk1M0&irgwc=1&sourceid=imp_TSnzBe1WKxycTBIzdBV78Wj9UksXXWT4Q2Dk1M0&veh=aff&wmlspartner=imp_27795&affiliates_ad_id=612734&campaign_id=9383&sharedid=6080654/"> Link </a> |
| L298N Motor Driver | Controls the DC Motors | $8.99 | <a href="https://www.amazon.com/Qunqi-Controller-Module-Stepper-Arduino/dp/B014KMHSW6/ref=sr_1_56?crid=2PXGS09EQWDRY&dib=eyJ2IjoiMSJ9.qawDn99TGs75N0slRxye4NsZmm8TPWyznPap_7RkjFdmPwBiu8gx-3hRNvV-zfTWtBJBeSLVCwXihOIE04jygL7pBm-Ek0idYs1YsAlKCfo.iM7rFy3oaCdNFqcC58Z5uXyjvNFD_EGVyWP9b9ZLaFA&dib_tag=se&keywords=single+l298n+motor+driver&qid=1750957714&sprefix=singlel298n+motor+driver%2Caps%2C174&sr=8-56&xpid=kqIxH__xzJ50_/"> Link </a> |
| Item Name | What the item is used for | $Price | <a href="https://www.amazon.com/Arduino-A000066-ARDUINO-UNO-R3/dp/B008GRTSV6/"> Link </a> |

# Resources
- https://lastminuteengineers.com/l298n-dc-stepper-driver-arduino-tutorial/
- https://randomnerdtutorials.com/complete-guide-for-ultrasonic-sensor-hc-sr04/
- https://www.instructables.com/How-to-Set-AT-Command-Mode-for-HC-05-Bluetooth-Mod/

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
