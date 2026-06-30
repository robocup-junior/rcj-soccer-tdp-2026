## Timestamp

*Tijdstempel*

10-6-2026 10:53:20

## Email Address

*E-mailadres*

hakyungi@hanmail.net

## TDP File

*TDP File Upload (Not required)*



## Team Name

*What is your team's name?*

K-ROMA

## League

*What league do you participate in?*

Vision League

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

![](images/1Al3q9r89MyCDYMySI8rhekeiloO2yGm6.jpg)

## Members & Roles

*What are the names of the team members and their role(s)?*

TAEAHN KIM : Electrical part
JEONGBEEN OARK : Mechanical part.
YEONWOO SONG : Software part.

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

160 minutes per week

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

Robotics academy

## Start Date

*When did your team start working on this year's robot?*

Nov 2025

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

Korea Open 2025 : Light weight league
Singapore Open 2025 : Light weight  League
Korea Open 2026 : VISION league

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

Mathematical theories such as trigonometry, inverse trigonometry, vectors, logical operations, and the drive system using four omni-wheels

## Workload Management

*How did you manage the workload?*

No special tools were used.

## AI Tools

*Which AI tools did you use?*

When special calculations such as driving formulas are required, ChatGPT and Copilot are used as references.

## Robot1 Overall

*Robot 1 Overall View*

![](images/1TtlyzZq23XHSPbNnzAiTmcjBIoXUkvye.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/11EfavSw-MQUAqZX41HyNR0nQBw-tlxlp.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1HuYU6by4Mv5SosOqxFnWmRCb0NleYGp8.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/12cHBtStyyUtBUGwFeabBudFNzHVoUeiI.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1GDa6aGim0Nw8pEkogmTWcA57XDmk9XUg.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/1MSH5pw0-dwklwbGFswGIl4H67UaPgNhD.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/1JQoh3stogno-Ay3O_Fej8nfzrBK6fX1u.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/1-_X1L1lOawYElxE1hoedsOYXHCNSL3H5.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/1z89qlOfrr94ThmZzU4xYcCjw5kUjsbKG.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/1taP_nzxy1l084_eEkWBntUUeGqHkDjWo.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/10yOyaT5-4d_yF27N_b1_I_UBEx1i12XP.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/132wApi2xS4UIZOACdGbTLqrnDuvJeMwJ.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1ls523ogNmf1T2qZziegfCw1RAJmrNWuV.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1KzWysWxCXZKeTotFmJhoytYKXLZ6m3Rz.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

Design - SKETCH-UP

## Build Method

*How did you build your design?*

3D Printing with FDM Printers and SLA Printer.

## Motors & Reason

*How many motors have you used and why?*

5 Motors.
4 Motors for driving and 1 motor for Dribbling.

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

We used a solenoid and is mounted directly to the PCB.

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*

We used a 16mm DC motor and a rubber roller for paper feeding used in printers, and they are connected by a timing belt.

## CAD Files

*CAD design files*



## Mechanical Innovation

*Mechanical Innovation*

It feels like a miracle that we managed to fit all the parts within an 18cm diameter.

## Mechanical Photos

*Photos of your mechanical designs highlights*

![](images/19Wdx8lHxD_JsHSjIlbTI2B10n6buIv8Q.jpg)

## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

![](images/1YDIyJdNoDRBECekvkydX8XcOBPyWJeFE.jpg)

## Power Circuit

*How does your power circuits work?*

11.1V 3S1P Lithium battery pack.
5V Switching regulator for digital devices.
3.3V linear regulator for TFT LCD.
5V to +12V,-12V DC-DC Converter for OP-AMPs.

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

We use 5-A H-Bridge for DC-Motor driver TLE5205-2G. Its operation is defined by IN1 and IN2 pins. We use ATMEGA2560's own PWM function to generate the signal and pass it to the driver.

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

We use Atmega2560 used in Arduino MEGA board. We chose it considering the 10 PWM signals, 3 UARTs, I2C, SPI, SOFTWARE UART, ADC and GPIO number we need. It has been a long time since we chose and used this CPU. Previously, we used ATMEGA2560 PRO module, but it took up a lot of space, so this time we directly attached CPU to PCB.

## Motor Control

*How do you use your processor to move your motors?*

Generator PWM.

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

There are 24 line detection sensors in total, each pair consisting of a white LED and a photo transistor.

## Line Detection

*How does your line detection circuits work?*

The current flowing through the phototransistor is converted into voltage by connecting a resistor, and then digitized using the ADC converter in the CPU for use.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

Currently, only the direction is controlled using the YAW value of the BNO055 IMU sensor.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

When the CPU sends an on/off signal, battery power is switched and used through the MOS-FET.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*

We use the same motor driver as the drive motor. It is controlled by a PWM signal.

## Schematics

*Schematics of your robot*



## PCB

*PCB of your robot*

![](images/1Vv1WdLXyBCSjBh041VgBPGFW9PeFnu9j.jpg)

## Electronics Innovation

*Electronics Innovations*

LED Dynamic Driving: 
We use 24 phototransistors for line detection. We use 24 WHITE LEDs as light sources. Each LED consumes 20mA. If we turn on 24 LEDs at the same time, 480mA of current will flow. We used two TLC6C5912, 12-bit Shift Register LED drivers to limit the number of LEDs that can be turned on at the same time.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1FXyZTOhK9jBgJSvSSsNJBZFVP4mTOS1m.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

The ball is basically detected by the camera through the reflector. The OpenMV camera finds the ball and each goal and sends the coordinate information to the CPU. DATA is when the CPU sends a request command to the camera, the camera sends all the information to the CPU.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

When the robot detects the ball with the camera, the robot draws a virtual circle on the ball, finds a point where the robot and the circle meet, moves to that point, and when it reaches the starting position, moves to the back of the robot along that virtual circle. If the ball is in front, it moves to the back of the ball.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

We use the BNO055 IMU sensor to control only the direction.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

We installed 24 light sensors. When a line is detected, the average of the physical coordinates of the sensors defined by the self is calculated. This value becomes the vector value of the direction in which the robot was moving. We move the robot in the opposite direction of this vector and move until the sensors that passed the line cross the line again.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

We use the ball's coordinates obtained from the camera to approach the ball from behind, following a virtual circle centered on the ball. And Shoot.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

We use the coordinates of the goal and the ball obtained from the camera to move the robot to the middle, thereby reducing the shooting angle.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

The robots communicate with each other. If no signal is received from the attack robot, the defense robot switches to attack, and switches back to defense when the signal is received again.

## Software Innovation

*Software Innovations*

Escaping from the line: When a line is detected, the average of the physical coordinates of the sensors defined by the robot is calculated. This value becomes the vector value of the direction in which the robot was moving. We move the robot in the opposite direction of this vector until the sensors that passed the line cross the line again.

## GitHub Link

*GitHub link*



## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=1Pk56FqrnB2n0EU3SBqQAQH35X5xH5Loo](https://drive.google.com/open?id=1Pk56FqrnB2n0EU3SBqQAQH35X5xH5Loo)

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

