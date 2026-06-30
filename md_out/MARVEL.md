## Timestamp

*Tijdstempel*

10-6-2026 7:14:32

## Email Address

*E-mailadres*

hakyungi@hanmail.net

## TDP File

*TDP File Upload (Not required)*



## Team Name

*What is your team's name?*

MARVEL

## League

*What league do you participate in?*

Vision League

## Country

*Where are you from?*

SOUTH KOREA

## Contact

*If other teams have questions about your robot, now or in the future, what email address(es) can we publish along with this document for people to reach you?

(You can put in multiple email addresses, like multiple team members, an email for the whole team or both. Feel free to share other ways of communication like Discord handles)*

hakyungi@hanmail.net

## Social Media

*Team Social Media Links (if you have any)*



## Team Photo

*Upload a photo of your whole team with your mentor and robots

Note: This is not mandatory and will be published along with your TDP if you choose to upload something*

![](images/1_OO6LDEl_C03K7Q-8FZvXn3AeLxX1hQa.jpg)

## Members & Roles

*What are the names of the team members and their role(s)?*

JUHO EOM : HARDWARE
SEOHYUN BYEON : SOFTWARE

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

160 Minutes per week

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

Robotics Room at robotics academy

## Start Date

*When did your team start working on this year's robot?*

Aug. 2025

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

Austrailia Open 2024 : Light Weight (EOM)
2024 Eindhovwn : Open Open League (BYEON)
Singapore Open 2025 : Open League (BYEON)
2025 Salvador : Open League

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

Technical theories and related mathematical theories such as trigonometry, inverse trigonometry, vectors, logical operations, and the drive system

## Workload Management

*How did you manage the workload?*

No special tools were used

## AI Tools

*Which AI tools did you use?*

When special calculations such as driving formulas are required, ChatGPT and Copilot are used as references.

## Robot1 Overall

*Robot 1 Overall View*

![](images/1AisOGDyxeCSEE1qt0mrGLzuj5YTAv5IX.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/1AvV2dBtnwkGERibmeWzy1n4bRhzjnMfY.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1crc2CLZ_3r2jdLZ59gRvGUskQJ6lrETP.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/1HNn45K-3X5BlH_hEn4oWi4beobFC3nJ5.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1apXucpjKezcWznEk2QHvXTh7mFU5mRcj.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/1QnnfxjIt50wzPaCEZflRpIdoGajiTiVm.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/15u5Fw713iAzc0vuPtsZQ7X5Oze69CoKo.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/1XXGTtz9NS5fnmgdO_gQCddGtY4Xr4Cin.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/1YO5ZkAIVqrITLSGCxXYv4CbDyGFRHL1x.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/1MY2g0hX9WqVVY-jnAT6KVcQjIyOI-qwt.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/1vK-F_Cbmmx6SP9JdxiAhjXtBEZRz3A5B.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/1_0gEA8V_Nw7Ym57TUzXsUzbbhxespUs1.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1O08MDqADE6SL0qDGahtR_WYXd4QJKROx.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1IyCJ3Zt_jOamM7-A0wbFOAslrfO8FMpr.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

Schematic and PCB design : OR-CAD
3D Printing : SKETCH-UP and slicer programs.

## Build Method

*How did you build your design?*

1. FDM & SLA 3D Printers
2. Mirror Making, PCB Making, SMT
3. Motor placement: Initially intended to be placed at 90-degree intervals, but due to the solenoid not fitting, the arrangement was changed to 11 degrees forward and 110 degrees backward.

## Motors & Reason

*How many motors have you used and why?*

5 Motors
4 Motors for driving : Planetary Gear Motors 730RPM part number 638260. Servocity, USA
1 motor for dribbler : GA16-050 planetary motor 2526RPM motor. AliExpress, China

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

Solenoid KK-1040B. AliExpress, China
Switching with MOS-FET IRFZ34N

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*

DC motor and a paper feed roller with timing belt.

## CAD Files

*CAD design files*



## Mechanical Innovation

*Mechanical Innovation*

3 wheels -> 4 wheels

## Mechanical Photos

*Photos of your mechanical designs highlights*

![](images/1p9i9a4zUi82W6-XWYcSC5o4Xq2B8ikFK.jpg)
![](images/1CTpkB-oF57j5TMoslfPJCAE31DcGYtsI.jpg)

## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

![](images/1whKL7B3z0SP01x9g06koje0f7UgGnhce.jpg)

## Power Circuit

*How does your power circuits work?*

11.1V lithium polymer battery. 5V Regulator for Digital devices. 3.3V regulators for LCD. +12V, -12V DC-DC conveter for analog OP-AMP.

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

5-A H-Bridge for DC-Motor driver TLE5205-2G. We use ATMEGA2560's own PWM function to generate the signal and pass it to the driver.

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

We use Atmega2560 used in Arduino MEGA board. We chose it considering the 10 PWM signals, 3 UARTs, I2C, SPI, SOFTWARE UART, ADC and GPIO number we need. It has been a long time since we chose and used this CPU. Previously, we used ATMEGA2560 PRO module, but it took up a lot of space, so this time we directly attached CPU to PCB.

## Motor Control

*How do you use your processor to move your motors?*

PWM

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

Open-MV Camera with custom made reflector. Photo coupler to detect front side.

## Line Detection

*How does your line detection circuits work?*

24 Photo transistors and 24 white LEDs. ADC with analog MUX.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

We use BNO055 sensor. Connected to CPU by I2C.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

On/Off Signal from CPU. It Switch MOS FET IRFZ34N.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*

The driving circuit of the dribbler is the same as the driving motor. It uses the Motor Driver TLE5205, and the CPU generates a PWM signal and inputs it to TLE5205 In1 and In2.

## Schematics

*Schematics of your robot*



## PCB

*PCB of your robot*

![](images/1sBK3XYLLECaoQeBmOePuNzxaVHGXgSFE.jpg)

## Electronics Innovation

*Electronics Innovations*

LED Dynamic Driving: 
We use 24 phototransistors for line detection. We use 24 WHITE LEDs as light sources. Each LED consumes 20mA. If we turn on 24 LEDs at the same time, 480mA of current will flow. We used two TLC6C5912, 12-bit Shift Register LED drivers to limit the number of LEDs that can be turned on at the same time. Currently, only 4 LEDs are turned on at the same time. If we are reading one sensor now, we only turn on the LEDs up to the 3rd sensor to be read.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1z3TtSM5SuwHeLDLo7740mKQ4N_rhjGlz.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

The ball is basically detected by the camera through the reflector.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

When the robot detects the ball with the camera, the robot draws a virtual circle on the ball, finds a point where the robot and the circle meet, moves to that point, and when it reaches the starting position, moves to the back of the robot along that virtual circle. If the ball is in front, it moves to the back of the ball.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

We used BNO055 sensor. We control only the direction.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

Boundaries are detected using light sensors. Determine the direction of travel through logical operations and move in the opposite direction.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

Using coordinates collected through the camera and mirror, approach the ball from behind, turn toward the goal, and shoot.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

Use the angle between the center of the goal and the ball to move the robot along that line and block the ball.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

The robots communicate with each other. The attack robot sends an ACK (0x064) every 0.2 seconds. If the defense robot does not receive this signal for more than 1 second, it considers the attack robot to have been kicked out and switches to attack immediately. If this signal is received again, it finishes what it was doing and switches back to defense mode.

## Software Innovation

*Software Innovations*

Escaping from the line:
The robot has 16 sensors placed at equal intervals on a circle. When a line is detected, the average of the physical coordinates of the sensors defined by the robot is calculated. This value becomes the vector value of the direction in which the robot was moving. We move the robot in the opposite direction of this vector until the sensors that passed the line cross the line again.

## GitHub Link

*GitHub link*



## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=1zRi_oLDC4DYCZ3hIel_Xf9AepgehpM2B](https://drive.google.com/open?id=1zRi_oLDC4DYCZ3hIel_Xf9AepgehpM2B)

## Cost

*How much did it cost you to build your robots?*

Robots (cost of components that are in your robots right now): 1,200 USD each
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

