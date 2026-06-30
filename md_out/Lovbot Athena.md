## Timestamp

*Tijdstempel*

29-6-2026 2:08:11

## Email Address

*E-mailadres*

tianaigu0902@gmail.com

## TDP File

*TDP File Upload (Not required)*



## Team Name

*What is your team's name?*

Lovbot Athena

## League

*What league do you participate in?*

IR League

## Country

*Where are you from?*

Canada

## Contact

*If other teams have questions about your robot, now or in the future, what email address(es) can we publish along with this document for people to reach you?

(You can put in multiple email addresses, like multiple team members, an email for the whole team or both. Feel free to share other ways of communication like Discord handles)*

lovbotathena@gmail.com

## Social Media

*Team Social Media Links (if you have any)*

https://www.youtube.com/@lovbotathena

## Team Photo

*Upload a photo of your whole team with your mentor and robots

Note: This is not mandatory and will be published along with your TDP if you choose to upload something*



## Members & Roles

*What are the names of the team members and their role(s)?*

Emma Zhou: Defense, Gameplay Strategies
Tony Shang: Mechanical Design, Electrical Design
Tina Gu: Offense, Documentation

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

Regular week:  15 hours a week; 3 weeks before the competition: 40 hours a week

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

Robotics Club

## Start Date

*When did your team start working on this year's robot?*

September 2025

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

2026 RoboCupJunior Western Canada Soccer Infrared 
2025 RoboCupJunior Québec Soccer Infrared
2025 RoboCupJunior Western Canada Soccer Infrared

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

Our mentors mainly helped with stabilizing the camera, dual IR receivers, and custom kicker electronics to improve robot reliability.

## Workload Management

*How did you manage the workload?*

Our team managed the workload by communicating effectively in an Instagram group chat. We also made schedules and to-do lists on Google Sheets to organaize and assign tasks.

## AI Tools

*Which AI tools did you use?*

We used YOLOv8 for object detection and Claude/ChatGPT to implement algorithms, simulate outputs, and optimize code structure.

## Robot1 Overall

*Robot 1 Overall View*

![](images/1KyEunHwR653CClJW9OxUysCjAnGgB6ie.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/1359C-sX5iKGRtwvSwdp4wZqCYzoIQCJq.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1lQUyuSZtaWDNTbXCG9OSfphpDIkrLzar.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/1Unp-f8qPiu6a9fxnBPbeHtOXMvcEVI_q.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1m600XnOJ0ZLf5CYfL1GgHBJjlytfkvW5.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/12x8vj9dADtMSkdfaOYj36z1F6kGKuGCG.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/1cHiRNeNN9Hp3vkvpq7ncY5HUh0--1HRL.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/170He5SH4PgbcOg9jjTSupwQ7E5P8mjAj.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/1UjwlKadlC7YYdDoeg7y-PP4HVqfRK7As.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/1XW8V6sPdCxnpNkEkDOVsPpWKGB3a848q.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/1GCuIRkaIARtJZEdv4Mzn_n8x8ngU5KUh.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/1QK8zGU_OI7KPot2Y2VG4mwucnn_riP6Y.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1j_9hYQr0FFt157VnGLZK4QOGmcx97UM5.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1tjty_c_FeGs4HxnbObSNuPaaQ1lhIyt_.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

We used SolidWorks to design and validate all mechanical components before manufacturing, allowing us to verify fit, clearances, and integration with the electronics. Through iterative prototyping, we lowered the omnidirectional IR ring and refined the layout into a more compact design while keeping every major subsystem modular, enabling fast maintenance, repairs, and component replacement.

## Build Method

*How did you build your design?*

We use 3D printers, laser cutting, and CNC to execute our CAD designs. Our PCBs were designed and manufactured by JLCPCB. We needed to revise parts of our robot, going through rigorous testing to ensure stability and to improve physical robustness.

## Motors & Reason

*How many motors have you used and why?*

We use four Pololu 12 V DC gearmotors arranged in an X-drive configuration, with a widened front track to maximize ball capture. The drivetrain provides fast omnidirectional movement, while our custom 3D-printed, hand-assembled omni wheels were optimized through extensive testing to achieve the best balance of weight, traction, and overall performance.

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

The 12 V battery is boosted to 48 V by a DC-DC converter before charging a capacitor bank with a total capacitance of 8,600 µF. When activated, the stored energy is rapidly discharged through a handcrafted solenoid surrounding an 8 mm steel pole, generating the force required to kick the ball.

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*



## CAD Files

*CAD design files*

https://github.com/lovbot-athena/cad

## Mechanical Innovation

*Mechanical Innovation*

We are particularly proud of our custom semi-circular housing for the omnidirectional IR sensor array. Through extensive testing, we optimized its spacing and opening geometry to maximize IR signal reception while minimizing physical obstruction. The housing also securely positions each sensor, reducing environmental interference and ensuring reliable, consistent ball detection throughout the match

## Mechanical Photos

*Photos of your mechanical designs highlights*

![](images/16REvwwl8YmMLNpUjPETocwrhKHRfwfUX.jpg)

## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

![](images/1Os6vJ8zy2Z3So-hEHgJwZzeLdJzB8E9a.png)

## Power Circuit

*How does your power circuits work?*

Our robot runs off a 12V battery that is routed through a switchboard. The 12V powers the motor drivers directly, and powers the Teensy, which uses a buck converter to step down to 5V. The switchboard can power the motors and Teensy separately.

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

We use two motor drivers to control our four motors, with each driver handling two. Each motor is controlled by two signals: a digital signal that determines direction, and a PWM signal to determine speed

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

We use a Teensy 4.1 as the main controller due to its 600 MHz ARM Cortex-M7 processor, abundant I/O, and large memory capacity. With 18 analog inputs and multiple digital and communication interfaces, it simultaneously supports the camera, ultrasonic sensors, compass, IR sensors, and motor drivers while providing the processing power required for reliable real-time sensor fusion and robot control.

## Motor Control

*How do you use your processor to move your motors?*

The Teensy processes sensor data in real time, calculates the desired robot movement, and outputs PWM signals to four motor drivers, which regulate the speed and direction of each motor for precise omnidirectional control.

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

Our MaixCam is mounted facing upward toward a custom convex mirror, providing a complete 360° view of the field. Using a trained YOLOv8 model, it recognizes the ball in real time. In addition, 23 TSSP58038 IR receivers mounted on custom PCBs detect the ball's infrared signal, producing analog outputs that estimate its direction and distance for fast, reliable ball tracking.

## Line Detection

*How does your line detection circuits work?*

We use 32 downward-facing grayscale sensors arranged in a circular array for accurate 360° white-line vector calculation. Each sensor detects reflected light, while analog multiplexers use four digital select lines to read all 32 sensors through just two analog input channels.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

For orientation, we use a BNO055 connected to the Teensy over I2C. To find our position, we use four ultrasonic sensors that measure the distance to nearby walls and estimate the robot’s position relative to the field boundaries. These sensors are connected to the Teensy through analog input pins. Our MaixCam is also used to approximate the robot’s position relative to the goal.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

The Teensy triggers the kicker by setting a digital control pin HIGH. A 12 V battery is boosted to 48 V to charge an 8,600 µF capacitor bank, which rapidly discharges through a handcrafted solenoid, accelerating an 8 mm steel pole to kick the ball.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*



## Schematics

*Schematics of your robot*

![](images/1M1UDx2d7TJQFDUp31J5CBCfvOL-DTavp.png)
![](images/1V_xIPG6O43sykLHUHKhXpLQAE2LAVn1P.png)

## PCB

*PCB of your robot*

![](images/1gnNZUmPerjqhTMKVqNwHDQj23Gkbcb_u.png)
![](images/1HlSiMTly3oEX5IIjedDiH6MrsxflT6B9.jpg)
![](images/1xYF2b-k14bL2y4Fv-8VYSS3FYVItzWEG.jpg)

## Electronics Innovation

*Electronics Innovations*

We are proud of our development of our custom electromagnetic kicker. Achieving reliable and consistent performance required extensive experimentation, as the output depended on many interrelated design parameters rather than a single component. We iteratively optimized the boost voltage, total capacitor capacitance, solenoid wire length, wire gauge, winding density, and the dimensions of the 8 mm steel pole. Small changes to any of these parameters significantly affected the kicking force and efficiency, requiring repeated testing and refinement. Through this iterative design process, we developed a stable kicker capable of delivering powerful and consistent shots while remaining compact enough to fit within the robot's mechanical constraints.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1QL9w5DXbIGqtG0Ic0h3i0mr6wPLVy1an.jpg)
![](images/1Eby5NjprmJdwMNG7YL5XrLHmUkJnua8m.jpg)
![](images/19RVwzdz74rPeGJFGq8C2HDAWwvs_DNI6.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

The robot finds the ball by weighing signals from two IR sensors and a camera into an algorithm that returns a precise angle. The IR sensors send 2 analog signals: the eye port and the strength of the signal to the Teensy, which can be used to determine the angle and distance to the ball. The camera views a convex mirror and detects the ball’s angle by reading the color and size of pixel clusters.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

Our robots curve behind the ball to capture it. It uses a tuned PID and an angle-based offset. The PID scales how sharply the robot curves based on a median filtered ball distance value, and swings wider when the ball is far away and straightens out as it approaches to avoid overshooting. This is multiplied by an angle ratio to produce a smooth arc that brings the robot behind the ball.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

We locate the robot using four ultrasonic sensors (front, back, left, right), each measuring its distance to a wall. Combined, these give Cartesian coordinates relative to the field's center. To reach a target, the robot takes the difference between the target and current coordinates on each axis and converts it into a heading, driving toward the target while staying forward-facing.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

Our main boundary detection system consists of a circular array of 32 grayscale sensors mounted beneath the robot. By combining the outputs of all sensors, the robot computes a vector representing the direction of the white boundary line, immediately drives in the opposite direction to remain in play, and uses ultrasonic sensors to reduce its velocity as it approaches the field boundaries.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

When our robot gains possession, it aligns with the opponent’s goal before shooting. Using ultrasonic distance measurements, it estimates its position on the field and calculates the optimal shooting direction. To avoid unnecessary rotation and maintain fast ball control, the target heading is constrained so the robot always turns along the shortest practical path toward the goal.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

Our goalie remains on the penalty line at all times to maximize goal coverage. A circular array of 32 grayscale sensors detects the penalty line and computes a vector to keep the robot on it. A second vector, perpendicular to the ball’s direction, moves the goalie laterally along the line. Combining these vectors keeps the goalie aligned with the ball while maintaining its defensive position.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

Yes. When the ball is far up the field, the defender cannot detect it accurately because of the increased distance. The offensive robot, being much closer, sends its more accurate ball position to the defender via Bluetooth. The robots also switch roles when needed, allowing the robot closest to the ball to attack while the other defends, improving ball recovery and team positioning.

## Software Innovation

*Software Innovations*

Our key software innovation is a sensor fusion algorithm that combines data from the omnidirectional IR sensor array, front precision IR sensor, and AI camera to accurately locate the ball. The algorithm continuously adjusts the weighting of each sensor based on its confidence, which changes with the ball's distance and position. By prioritizing the most reliable sensor while filtering noisy measurements, the robot maintains a fast, accurate, and robust estimate of the ball throughout the match.

## GitHub Link

*GitHub link*

https://github.com/lovbot-athena/lovbot-athena

## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=1N0naSnDQOEgQr_p5h8BTl6M5HHjabpw1](https://drive.google.com/open?id=1N0naSnDQOEgQr_p5h8BTl6M5HHjabpw1)

## Cost

*How much did it cost you to build your robots?*

Robots: 2954.82 CAD
Experiments/Broken Parts: 3500 CAD
Environment: 500 CAD
1 CAD = 0.70 USD

## Funding

*How did you gathered the funds to build the robots?*

100% parents

## Affordability

*How affordable was it to compete in RoboCupJunior Soccer?*

8

## Answer Check

*Have you checked all of your answers?*

Yes!

## Publication Consent

*We publish TDPs and posters during or after the competition as described in the beginning*

Yes, we acknowledge everything submitted in the above form can be published.

