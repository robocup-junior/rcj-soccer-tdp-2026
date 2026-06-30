## Timestamp

*Tijdstempel*

28-6-2026 16:53:14

## Email Address

*E-mailadres*

team.lares.official@gmail.com

## TDP File

*TDP File Upload (Not required)*



## Team Name

*What is your team's name?*

Lares

## League

*What league do you participate in?*

Vision League

## Country

*Where are you from?*

Republic of Korea

## Contact

*If other teams have questions about your robot, now or in the future, what email address(es) can we publish along with this document for people to reach you?

(You can put in multiple email addresses, like multiple team members, an email for the whole team or both. Feel free to share other ways of communication like Discord handles)*

team.lares.official@gmail.com

## Social Media

*Team Social Media Links (if you have any)*



## Team Photo

*Upload a photo of your whole team with your mentor and robots

Note: This is not mandatory and will be published along with your TDP if you choose to upload something*



## Members & Roles

*What are the names of the team members and their role(s)?*

MinJun Jung: Offense programming

SiYoung Kim: Defense programming

TaeSeob Yoon: Robot hardware

GunYul Park: Robot hardware

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

for over 5 hours every Saturday

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

at some other place

## Start Date

*When did your team start working on this year's robot?*

Continuously since 2025

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

2024 Netherlands: Soccer LW
2025 RCKO: Soccer LW
2025 Brazil: Soccer LW
2025 RCAP Dubai: Soccer Open
2026 RCAP Korea: Soccer Vision
2026 RoboCup China Open: Soccer

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

​Our mentor helped us refine our robot's movement strategy to perform more efficiently during matches.

## Workload Management

*How did you manage the workload?*

We used Notion to divide tasks among team members, refine schedules, and share and record the TDP production and development process in real-time. I also managed the code using GitHub.

## AI Tools

*Which AI tools did you use?*

We used ChatGPT, Gemini, Claude to support brainstorming, algorithm comparison, and preparation of documentation.

## Robot1 Overall

*Robot 1 Overall View*

![](images/1euah4CZ-QIrFFLLEKZn_cZxba7B99_lK.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/1ULay4CClSjC8S0HKe1MyxqmBxn1jtaki.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1VM_zp7HUu4yVViv0XCFZ6Dot-NlxjPge.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/1JZqjvtKEW378B320rKBfHAWJ8aHV_Jwo.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1urAh1zLsN8j_JwtId5xM2U4cOGh405Wp.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/1KlqEkbac3zgPBHU6ZhbogQCaaqwx6bJl.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/1AzQK7f_AYzHJGIjk_PU399Ys0-TWXNN8.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/1AJZTM8Gv6UJ19h43SGwy1IRcH8qtZ0Tt.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/185bY1x3EqQ5iwAZt6U2pEoSYCIxg-JEy.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/1dRHKOD8EscvEiIrT1RvXqhB2PIZD5ZcS.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/17X4CB69IpOEOA842AuMztHr7ya37fprg.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/1mXNAOP5KxY9HSPpBEtvVEC8BaFlF0rV7.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1F_ZTvSqsw0qCHYgnZsCuzSDoA2Aup8F0.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1URIi2EAKUTaETyf8IphXOCpu6NC1wzy6.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

We designed compact holonomic robots that can move in any direction while controlling their heading. We considered size, weight, camera visibility, sensor placement, ball control, maintenance, center of mass, and protection from collisions.

## Build Method

*How did you build your design?*

We assembled the robots using custom-made and commercially available parts. During the building process, we adjusted the structure, component positions, and wiring based on testing to improve reliability, maintenance, and overall performance.

## Motors & Reason

*How many motors have you used and why?*

The robot uses four drive motors and one dribbler motor. Four drive motors allow holonomic movement in any direction.

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

We designed a solenoid-based kicker. We optimized the spring mechanism and internal circuitry to achieve maximum force while maintaining a compact size.

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*

Our dribbler uses a high-RPM DC motor attached to a rubber-coated roller. We designed the housing to firmly hold the ball against the robot's body to maintain control during movement.

## CAD Files

*CAD design files*

N/A

## Mechanical Innovation

*Mechanical Innovation*

The robust design provides excellent durability during intense matches. However, it has a maintenance issue where we have to disassemble the entire chassis for even minor repairs. Therefore, we plan a complete redesign after this competition to adopt a modular structure while maintaining the same durability

## Mechanical Photos

*Photos of your mechanical designs highlights*



## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

![](images/1dBA6YkUKfO06JcnyHNcC8n_gqFMmNwyp.png)

## Power Circuit

*How does your power circuits work?*

The robots use an 11.1 V 3S Li-Po battery. Motor drivers use the battery supply directly, while regulated voltage is provided to the Arduino, camera, sensors, and display.

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

The Arduino sends PWM and direction signals to separate motor drivers. Each motor is controlled independently. The software combines X movement, Y movement, and rotation, then converts them into individual wheel outputs.

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

We use an Arduino Mega 2560-based controller because it has many I/O pins, timers, serial ports, and PWM outputs. An OpenMV H7 Plus handles image processing separately and sends processed data to the Arduino.

## Motor Control

*How do you use your processor to move your motors?*

The Arduino calculates X-axis movement, Y-axis movement, and rotational correction. These values are converted into four wheel commands. Compass feedback is used for heading control, and all outputs are limited before PWM is applied.

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

The OpenMV H7 Plus detects the ball and goals using LAB color thresholds and blob filtering. It calculates object angle and distance, then sends the processed results to the Arduino through a fixed UART packet with a checksum.

## Line Detection

*How does your line detection circuits work?*

The robot uses 24 downward reflectance sensors, including 16 inner sensors and eight outer sensors. Their values are calibrated and thresholded. The positions of active sensors are combined to estimate the line direction.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

We use a BNO055 IMU for heading, four VL53L1X ToF sensors for wall distance, an OpenMV camera for the ball and goals, and 24 line sensors for the field boundary. We do not use wheel encoders.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

The Arduino controls a high-current switching circuit that powers the solenoid. A MOSFET or transistor handles the current, and a protection diode suppresses voltage spikes. The software forces the kicker off after about 300 ms.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*

The dribbler motor is powered through a separate motor driver controlled by the Arduino. A rotating roller contacts the upper part of the ball and pulls it toward the robot during capture, movement, and shooting alignment.

## Schematics

*Schematics of your robot*



## PCB

*PCB of your robot*



## Electronics Innovation

*Electronics Innovations*

We separate vision processing and real-time control. The OpenMV processes images, while the Arduino controls motors and sensors. We also distinguish normal object loss from communication failure and use 24 sensors for detailed line detection.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1YsTgG6h3N3l4CGzRMniZFmweyXK6SMeU.jpg)
![](images/1Rv_5Xbqy_5gxBeeiTMacrjOL9W-_o2DK.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

The OpenMV detects the ball using LAB color thresholds and filters blobs by size, shape, and position. It converts the selected blob into an angle and estimated distance, then sends the result to the Arduino through UART.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

The offensive robot combines a direct vector toward the ball with a tangential vector around it. This helps the robot move behind the ball instead of pushing it sideways. Near capture, sideways motion is reduced.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

The robots do not calculate a complete global position. They use IMU heading, goal direction, ToF wall distances, and line sensors to estimate only the information needed for each movement and defensive position.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

The software combines the positions of active line sensors into a line vector. It then calculates a safe escape direction and removes movement components that would push the robot farther outside the field.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

After capturing the ball, the offensive robot detects the opponent’s goal and calculates a target heading. The heading is filtered and rate-limited. The kicker fires only after ball capture and alignment conditions are satisfied.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

The defensive robot tracks the ball laterally and uses rear and side ToF sensors to stay near the center of its own goal. It moves to block the predicted ball path and can clear the ball during long deadlocks.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

No. The robots do not communicate with each other. Each robot makes decisions independently using its own camera, IMU, ToF sensors, and line sensors. Their offensive and defensive roles are fixed.

## Software Innovation

*Software Innovations*

Our main software innovation is combining direct ball approach and tangential orbit vectors with separately adjustable powers. We also use vector-based line escape, robust camera packets, heading filtering, and forced kicker shutdown.

## GitHub Link

*GitHub link*

N/A

## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=1wYCqfBQYo9Kw7gzfA3bcejRKfB_gU43B](https://drive.google.com/open?id=1wYCqfBQYo9Kw7gzfA3bcejRKfB_gU43B)

## Cost

*How much did it cost you to build your robots?*

Robots: approximately 1,500,000 KRW (USD 977) per robot
Total for two robots: approximately 3,000,000 KRW (USD 1,954)

## Funding

*How did you gathered the funds to build the robots?*

100% parents

## Affordability

*How affordable was it to compete in RoboCupJunior Soccer?*

6

## Answer Check

*Have you checked all of your answers?*

Yes!

## Publication Consent

*We publish TDPs and posters during or after the competition as described in the beginning*

Yes, we acknowledge everything submitted in the above form can be published.

