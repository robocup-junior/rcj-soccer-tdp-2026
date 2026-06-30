## Timestamp

*Tijdstempel*

28-6-2026 19:31:22

## Email Address

*E-mailadres*

airkorea2026@gmail.com

## TDP File

*TDP File Upload (Not required)*



## Team Name

*What is your team's name?*

AIR

## League

*What league do you participate in?*

IR League

## Country

*Where are you from?*

Japan, Shiga

## Contact

*If other teams have questions about your robot, now or in the future, what email address(es) can we publish along with this document for people to reach you?

(You can put in multiple email addresses, like multiple team members, an email for the whole team or both. Feel free to share other ways of communication like Discord handles)*

airkorea2026@gmail.com  Tanuki.1116.au@gmail.com

## Social Media

*Team Social Media Links (if you have any)*

X:https: //x.gd/T2k8g  youtube: https://x.gd/7BVjx

## Team Photo

*Upload a photo of your whole team with your mentor and robots

Note: This is not mandatory and will be published along with your TDP if you choose to upload something*

![](images/1ZuMMuKwbNAqdicVXsteSplnO9dhIHmxs.jpg)

## Members & Roles

*What are the names of the team members and their role(s)?*

Asahi Uchida : Captain, Circuit & PCB design, Programming, Poster Design
Kengo Nakazawa : Hardware design
Kosuke Kano : Programming, Corporate Relations Lead
Yumiko Uchida: Mentor

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

Five times a week for two hours.

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

Robotics club and Innovation Center at School.

## Start Date

*When did your team start working on this year's robot?*

Started after RCJ2025 Salvador in Brazil.

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

Japan Open 2020 ~ 2021: Soccer Entry League
Japan Open 2022 ~ 2025 : Soccer LightWeight League
RCJ2025 Salvador in Brazil : Soccer LightWeight League
Japan Open 2026 : Soccer Infrared League

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

We asked our mentor to buy our daily development tools and supplies.

## Workload Management

*How did you manage the workload?*

We used Discord for communication and GitHub for managing tasks and software. We also utilized Notion to manage our schedules, goals, development notes, and task assignments.

## AI Tools

*Which AI tools did you use?*

We leveraged AI for faster debugging, code fixes, and English translations, significantly boosting development speed.

## Robot1 Overall

*Robot 1 Overall View*

![](images/1q7uzlQ3_nWJ4n8t40x9jiZr9uxp4hrMc.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/1Nz2UiywQpFHSauFsB20EQ30iqubYh_jM.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1KFJi6s8pRUKpT5Bp3OR_Vb5EOIi2Mms4.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/1n9SCf3app3OZhUQ51y0Vwj2TFC6uMnTV.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1KPClkEa999_W-7RQCPylNWFxPisG-Zid.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/1faquXMKwfraTacy8bX61_3soAYoi4l9l.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/1AZfXYVBV3AVJ2-RptXSWhC4-Hw4HhYI6.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/16pKHypzptOoW01PdaBGVAItRzjv_fII2.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/1zXe3hLJmWFMSNLS1s5VOZnY5KGWb5FwI.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/1MbnQ-GvsO1oah7dslF4eKnYU7aX0ezw9.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/1Kj7RC0IjK3zWq7VoCv_qezrW2zgxp8uY.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/1focJSM_aVfZ6mbtXeEIiybWivQqGWbO1.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1mVNAIJPLwpRLUMIr8eWCC-V8INS_td_W.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1aZC_JQ8XDFiLK0IGmc5BFpLd9WJjVUOp.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

We use Fusion 360 for 3D modeling and 3D-printed parts to build our robot. We designed a wide ball-sensor array to easily detect the ball while keeping the sensor ring as low-profile as possible. Balancing full functionality while meeting all the tournament's strict physical constraints was a major challenge.

## Build Method

*How did you build your design?*

All frames are built in-school using CNCs and 3D printers; we don't outsource. PCBs are sponsored by JLCPCB. After JapanOpen, the smaller ball required a larger board diameter, leading us to redesign both our main and ball-sensor board structures.

## Motors & Reason

*How many motors have you used and why?*

Both robots use 4WD for high torque, outpushing 3-wheel drives. Reaching the limits of cheap $15 motors, we upgraded to Maxon DCX (Robot1) and RE16 (Robot2). For durability, each sub-roller has an individual shaft with washers. After testing silicone and 3D spikes, we chose thin, laser-cut urethane for wear resistance. We also used dual-layered omni wheels to increase friction based on last year.

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

The solenoid was installed at half the height of the ball with a small gap in between to increase the range of instantaneous acceleration, transmitting the impact to the ball more effectively.

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*

Our dribbler system activates only when front sensors detect the ball. Powered by a 1410 BLDC motor and its included ESC, it is controlled via PWM signals from the main MCU. This allows precise speed management and bidirectional rotation for stable ball control during games.

## CAD Files

*CAD design files*

https://github.com/Gamu2124/RCJ2026-Korea_CAD-design-files

## Mechanical Innovation

*Mechanical Innovation*

Our robot has a dribbler built for tight spaces. We used a size 1410 BLDC motor as the actuator. Power is transmitted from the pinion gear on the motor shaft to the rotor gear via an intermediate shaft. For the roller that contacts the ball, we used a silicon tube to ensure high grip. For fabrication, we used a CNC machine to mill the main structural parts for durability, while a 3D printer was used for intricate, complex components.

## Mechanical Photos

*Photos of your mechanical designs highlights*

![](images/1TvgA6aYz8UBWiSlzZzd5--iX4KFHK0Y2.jpg)
![](images/1tJFYxJKlzRhL_qAhXR6hLdogS6ICj4C8.jpg)
![](images/1pWgRt32zktO67GksgnIQ2dVMcOc8esTZ.jpg)
![](images/18SeDir2VWw5YPoQu7feYMjMTZL-3PidJ.jpg)
![](images/1Zzs2lLzNkgYFswmzbxbFFKYasMmeoWIJ.jpg)

## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

![](images/18_GozWlsGm80XoX4FE9mKQfX_eN1SOrU.png)

## Power Circuit

*How does your power circuits work?*

Using 11.1V LiPo, our PDB steps down to 7V and 3.3V via DC-DC converters. The 3.3V powers motor and line boards. The 7V goes to the main board, further split into 5V and 3.3V via linear regulators. This post-JapanOpen2025 upgrade stabilizes MCU input waveforms by avoiding DC-DC noise.

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

Both robots use DRV8432 motor drivers, operating with the main power and 3.3V. PWM signals are sent from the main MCU. The DRV8432 was chosen for its 500kHz PWM, LAP control support, wide voltage range, compact size, and ability to drive two motors per chip.

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

Our main MCU is the Teensy 4.1, featuring a 600MHz processing speed and abundant GPIO/UART pins. To read all sensors directly, we adopted the RP2350A for ball sensors and the RP2350B for line sensors due to their optimal pin counts and processing speeds. For accurate goal tracking, we use three M5Stack UnitV2 AI Cameras, each with an internal dedicated MCU. Additionally, Seeed Studio XIAO ESP32-S3 modules are utilized for the debugging UI and ultrasonic sensor processing.

## Motor Control

*How do you use your processor to move your motors?*

Using Teensy 4.1, we control motors via 100kHz PWM. Motor drivers use duty cycles for speed. With LAP control, PWM values at 128+ run forward, and under 128 run reverse. Each motor speed is calculated via: sin(radians(goAngle - motorAngle[i])) * speed + nowDIR.

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

We use 24 TSSP58038 sensors for ball detection, wired directly to the RP2350A's digital pins via 3.3V, GND, and signal lines. For vision, we chose M5Stack UnitV M12 AI Cameras for their high scalability and ease of debugging. Although they support onboard AI, we bypassed this feature to maximize processing speed. They connect to the Teensy 4.1 via 5V, GND, and UART, communicating at a baud rate of 115,200.

## Line Detection

*How does your line detection circuits work?*

For line detection, we use 32 sets of B19H1LS phototransistors and OSHR1608 LEDs. Driven at 3.3V, they output analog signals via resistors, converted to digital by LM393 comparators for fast MCU detection. Separate bar sensors use wired-OR circuits to combine signals, all wired to the RP2350B.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

For navigation, we use RCW-001 ultrasonic sensors to detect walls and prevent going out of bounds. They connect digitally to a Seeed XIAO ESP32S3, which sends data to the main MCU via UART. For orientation, we use a BNO055 9-axis IMU. The robot tracks its heading using the onboard-calculated yaw angle. This sensor is directly wired to the Teensy 4.1 via I2C.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

Our kicker uses a Takaha CB1037 solenoid. A Teensy 4.1 signal triggers a P-ch MOSFET to charge capacitors to 46V via XL6009. A kick signal then fires an N-ch MOSFET to discharge power. A flyback diode protects against counter-EMF, and all digital signals are isolated via AQW212 photo couplers.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*

When the catch sensor in the hold area detects the ball, a PWM signal is sent to a commercial 20A ESC to spin the rotor. The rotor speed is dynamically controlled—low for forward driving and high for reversing—enabling stable, ideal ball handling.

## Schematics

*Schematics of your robot*

![](images/1hpuq498XgjJCLQJGhSWhoV7bYp3chFSU.png)
![](images/1VvyKwOB74iFG2XhZIHIuo_GOFz2jCp7Z.png)
![](images/1HfrGLitQS12wA1e_uvtNkyvo_1Q5-C39.png)
![](images/1-OKsF0QL9i1aYFumMS6jc7PcX1WMe1q-.png)
![](images/1SWi5ZGaWoUzBg_kM_oY_6-R5nhTHCAbB.png)

## PCB

*PCB of your robot*

![](images/1LgNCb_diAQ06yOzCAnMLO44kc0J52Wof.png)
![](images/11EYbxWMD-6pB4R1xk3I7XwK5jMlc0gVg.png)
![](images/18EFOg0URPTRPFv_4idYr3sje2UmHyxcd.png)
![](images/1UUvAJdIq3kULiVPcs69eTUdIbd2KFmOR.png)
![](images/1Dacb8SBYmp2hXPq4oqYXS2pXPNt_Lpcw.png)

## Electronics Innovation

*Electronics Innovations*

A major innovation in our electronic circuitry is the development of a highly stable and robust power supply system. Right before the JapanOpen, our robot suffered from frequent, critical resets of the Teensy 4.1 due to flawed DC-DC converter wiring and poor overall power design, presenting a fatal vulnerability for competition. To resolve this, we conducted a thorough overhaul, evaluating everything from component selection to PCB layout and noise suppression.

Our previous configuration stepped down a LiPo 11.1V input directly to 5V (3A) using an LM2576 DC-DC converter to power the Teensy 4.1. While this managed basic voltage delivery, it was severely inadequate regarding current capacity and noise management. Specifically, a single 3A output was forced to power three cameras, three microcontrollers, and a display, leaving the system hovering unpredictably on the brink of power starvation. Furthermore, because a DC-DC converter generates voltage by high-frequency switching through an inductor, significant switching noise inevitably contaminated the output waveform, preventing a clean power supply.

To overcome these flaws, we engineered an optimal, two-stage regulation topology: the LiPo 11.1V input is stepped down to 7V (5A) via an AP64500SP DC-DC converter, and then refined to an ultra-clean 5V (2A) via a BD50FD0 LDO to supply the Teensy 4.1. Crucially, we completely overhauled our PCB wiring design—a factor we had previously overlooked—to strictly adhere to the manufacturer's datasheet guidelines, optimizing the high-frequency current loops and component placement. This overall configuration features a wide input voltage range across both stages, offering robust protection against severe voltage surges. By leveraging a logical approach—utilizing the high-efficiency DC-DC converter to secure a massive 5A current capacity, and subsequently passing it through the low-dropout regulator to completely eliminate switching ripple noise—we achieved an ultra-clean voltage waveform. This circuit breakthrough successfully enhanced our core concept: building an indestructible and fundamentally reliable robot.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1_q8kkAfJDHLM1iUc07Wu7Bla_16phB4e.jpg)
![](images/1VUPQ1N4UfPc3YXxwmtsjTDdigh0Sl6hu.jpg)
![](images/1CGcrrt1qO4B9410SatibgUft4yG-lVot.jpg)
![](images/1qUwmUZVqZdR7Vrvbkt0d_JAkfl8jy99T.jpg)
![](images/1Y-UKSu7EAQV_dnw4TRUVEOyRKXDl3z_a.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

Ball tracking uses 24 TSSP58038 sensors in a ring. For heading, inputs are sampled 500 times; a weighted atan2 evaluates the 7 closest sensors. For distance, the Pythagorean theorem processes pulse widths from 12 sensors. Data is smoothed via EMA, and the RP2350 completes all calculations within 1ms for real-time tracking.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

The attacker uses ball coordinates to execute optimal wrap-around maneuvers, adapting to stationary, vertical, or lateral ball movements. The defender utilizes line-tracing to position itself perpendicular to the ball. High-speed and diagonal shots are easily intercepted due to our real-time tracking, limiting opponents to just one goal at JapanOpen.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

An RCW-001 ultrasonic sensor tracks wall distances to pinpoint field coordinates. This localization drives a dynamic speed control algorithm: the robot cruises at maximum velocity near the center to minimize travel time, but rapidly decelerates upon approaching walls to guarantee line-out prevention. This enables high-speed navigation without sacrificing stability.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

A 32-sensor bottom array detects white line clusters to find their average angles. By vector-adding all clusters, we get the line vector's total angle and magnitude. The vector dot product verifies if the robot has crossed halfway. To escape, it moves at the line angle plus 180°. Combined with ultrasonic wall detection, this algorithm prevents line-outs.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

We engineered a feint-based evasion algorithm that integrates the camera, dribbler, and kicker upon capturing the ball, representing our most innovative software breakthrough of this year. Additionally, when the ball is located on the goal side, the robot utilizes the dribbler to retain possession while driving downward to set up and target a shot.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

1. Localization Tracing: Localizes via sensors/cameras. Synthesizes vectors and adjusts gain/speed dynamically for stable boundary movement.
2. Goal Recovery: Returns if out of zone. Uses camera (dist/dir) for shortest path, minimizing defensive gaps.
3. Dynamic Roles: 3s possession triggers offense. Sidesteps opponents before kicking for precise clears or passes.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

Robots exchange role information via mutual communication between Seeed Studio XIAO ESP32S3 modules. We implemented a fail-safe logic where if the defender goes out-of-bounds, the attacker detects this status and immediately switches to a defensive role. This dynamic coordination eliminates defensive gaps.

## Software Innovation

*Software Innovations*

Our feint-based evasion is our top software innovation. Recognizing that reactive robots cannot handle sudden cutbacks, we built a system that dynamically switches two phases based on distance. Phase 1 (Close) uses split visual blobs from defenders to shoot into wide areas. Phase 2 (Long) drives into narrow goal spaces to manipulate enemy tracking, triggering a sharp cutback opposite when space vanishes. This forces sensor delays and tire slippage, securing victory.

## GitHub Link

*GitHub link*

https://github.com/Gamu2124/RCJ2026-Korea_Software-files

## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=1rDOgmtGxvh-ciL8IXJ9ny1NQ6SBzUW9t](https://drive.google.com/open?id=1rDOgmtGxvh-ciL8IXJ9ny1NQ6SBzUW9t)

## Cost

*How much did it cost you to build your robots?*

Robots : 1200 USD each
Experiments : 3000 USD for RCJ2021 ~ JapanOpen2026
Environment : 1500000 yen
1 yen = 0.62 USD

## Funding

*How did you gathered the funds to build the robots?*

60% sponsors
15% school
25% parents

## Affordability

*How affordable was it to compete in RoboCupJunior Soccer?*

1

## Answer Check

*Have you checked all of your answers?*

Yes!

## Publication Consent

*We publish TDPs and posters during or after the competition as described in the beginning*

Yes, we acknowledge everything submitted in the above form can be published.

