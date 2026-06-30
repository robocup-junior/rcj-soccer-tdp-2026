## Timestamp

*Tijdstempel*

10-6-2026 9:16:39

## Email Address

*E-mailadres*

hakyungi@hanmail.net

## TDP File

*TDP File Upload (Not required)*



## Team Name

*What is your team's name?*

Neighbor

## League

*What league do you participate in?*

IR League

## Country

*Where are you from?*

South Korea

## Contact

*If other teams have questions about your robot, now or in the future, what email address(es) can we publish along with this document for people to reach you?

(You can put in multiple email addresses, like multiple team members, an email for the whole team or both. Feel free to share other ways of communication like Discord handles)*

hakyungi@hanmail.net

## Social Media

*Team Social Media Links (if you have any)*



## Team Photo

*Upload a photo of your whole team with your mentor and robots

Note: This is not mandatory and will be published along with your TDP if you choose to upload something*

![](images/1tqshcUeVe4tIO0ivgvUD3NrU4FhyWBNu.jpg)

## Members & Roles

*What are the names of the team members and their role(s)?*

BEOMJUN KIM : Hardware
DOYUN KIM : Software

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

160 minutes per week.

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

Robotics academy.

## Start Date

*When did your team start working on this year's robot?*

Nov 2025

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

Korea Open 2026 Infrared League. it's first time for ROBOCUP competetion.

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

Basic rules.

## Workload Management

*How did you manage the workload?*

We didn't manage it specially, and every time we gathered, we organized the work to be done that day and divided up the work to be done.

## AI Tools

*Which AI tools did you use?*

No.

## Robot1 Overall

*Robot 1 Overall View*

![](images/1-X7kcuq1_Bsg8IUC7lCSeMSsgphBtJaj.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/1o7LXxDvxFtvsS4aAl53HeI0_XLjLkNCn.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1fbT1i-jBxIyH3C90-0J64hYoly4dV4MP.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/1TF_7YVj4jep-OGw9vYFfbPDQQ3WYe90p.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1wztmlU8v9TmpHhrdJKfb9Rxnrll0sMa5.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/1xIg08yq43uxzZede8pR1wkqWdKup-g7o.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/15VV_7KDPG_ET84N-ZSOM9D36GT0V5qbR.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/1bE9jhV6RcbzuYAeICouqrKXZrGluMznB.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/17mXd90jdqPIVf0Gn74L2xhuBs_RodDsn.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/14tYlPgSJgglxjVzuznZzJZOqaOChSpqW.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/1Etvqlpp8pGBUuirfLSHZr95ubMrINb8h.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/1Vre903nQ1QxX4rmGHKa8O-dTAZt-cIGc.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1Dn0BC2j-o3-RO9n0sgizVwjOIcT38UFv.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1l-ibBXcIvFRUBZLZk4__Q0cbpNKSHeLg.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

we designed with Sketch-Up program. And printing 3D Models.

## Build Method

*How did you build your design?*

FDM Printer & SLA Printer.

## Motors & Reason

*How many motors have you used and why?*

4 motors for driving and a1 motor for dribbler.

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

We used KK1040B solenoid with MOS FET IRFZ34N.

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*

The dribbler was made using a 16mm DC motor and a paper feed roller used in a printer

## CAD Files

*CAD design files*



## Mechanical Innovation

*Mechanical Innovation*

Four driving motors, a dribbler, and a solenoid were all packed inside a space with a diameter of 18 cm.

## Mechanical Photos

*Photos of your mechanical designs highlights*

![](images/1HgLtAZM22PBdbC0QsOxhG0GC0BjmxNVg.jpg)

## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

![](images/1uJQZjhYrXlbQFyMKfl0z3PaKuu5qB_sm.jpg)

## Power Circuit

*How does your power circuits work?*

Our robot can be powered by one 11.1V lithium polymer battery.
The motor and solenoid use the battery voltage as is, and use the 5V switching regulator LM2576 to make 5V and supply it to the logic.
3.3V linear regulator LM1117 and supply it to the LCD.

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

We use 5-A H-Bridge for DC-Motor driver TLE5205-2G. Its operation is defined by IN1 and IN2 pins. We use ATMEGA2560's own PWM function to generate the signal and pass it to the driver.

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

1: Atmega2560 - Main CPU
2: Atmega328 - IR Seeker
3: OpenMV Camera - ARM processor

## Motor Control

*How do you use your processor to move your motors?*

PWM

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

We used 11 Photo-TR ST3811 with band pass filer for short range about 150cm.
 We used Remocon Receiver TSOP4840 for long range about 4 meter.

## Line Detection

*How does your line detection circuits work?*

24 Photo transistor with white LED.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

We used BNO055 IMU sensor for direction.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

On/Off switching with MOS-FET IRFZ34N.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*

We used 5A Motor driver TLE5205. It works with PWM Signal.

## Schematics

*Schematics of your robot*



## PCB

*PCB of your robot*

![](images/1tD5OYcFlA7WKH9GRkx0I8lrUDP2knr8J.jpg)

## Electronics Innovation

*Electronics Innovations*

LED Dynamic Driving: 
We use 24 phototransistors for line detection. We use 24 WHITE LEDs as light sources. Each LED consumes 20mA. If we turn on 24 LEDs at the same time, 480mA of current will flow. We used two TLC6C5912, 12-bit Shift Register LED drivers to limit the number of LEDs that can be turned on at the same time. We can limit the number of LEDs that can be turned on at the same time with this part. Currently, only 4 LEDs are turned on at the same time. If we are reading one sensor now, we only turn on the LEDs up to the 3rd sensor to be read.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1Cg7Tn8-jn85zgcBiUsLE6T776qrEU_44.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

The nearby ball is found using 12 photo transistors with band-pass filters, and the far-away one is found using 8 remote control receivers.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

It approaches the back of the ball using the direction of the ball and the intensity of the infrared reception. Then, when IR is detected by the phototransistor in the capturing zone, the ball has entered the capturing zone.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

We used 24 Photo Transistors with white LED.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

When a line is detected, the average of the physical coordinates of the sensors defined by the self is calculated. This value becomes the vector value of the direction in which the robot was moving. We move the robot in the opposite direction of this vector and move until the sensors that passed the line cross the line again.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

When the IR VALUE in front increases, the dribbler is activated, and when the ball is detected by the IR Sensor in the capturing zone, a shot is taken.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

We do not have a defensive program yet.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

No. However, a Bluetooth module exists in the hardware.

## Software Innovation

*Software Innovations*

The ball is located by combining analog and digital signals. It is located at close range using a phototransistor and at long range using a remote control receiver.

## GitHub Link

*GitHub link*



## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=14JdBSqELQIJOPb5eHpTYr06KxO8mGBW_](https://drive.google.com/open?id=14JdBSqELQIJOPb5eHpTYr06KxO8mGBW_)

## Cost

*How much did it cost you to build your robots?*

Robots (cost of components that are in your robots right now): 1,400 USD each
Experiments (failed builds, broken hardware etc.): 1,500 USD
Environment (fields, balls, etc.) : 200 USD

## Funding

*How did you gathered the funds to build the robots?*

80% ACADEMY
20% PARENTS

## Affordability

*How affordable was it to compete in RoboCupJunior Soccer?*

3

## Answer Check

*Have you checked all of your answers?*

Yes!

## Publication Consent

*We publish TDPs and posters during or after the competition as described in the beginning*

Yes, we acknowledge everything submitted in the above form can be published.

