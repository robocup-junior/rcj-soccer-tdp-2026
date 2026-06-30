## Timestamp

*Tijdstempel*

27-6-2026 16:47:38

## Email Address

*E-mailadres*

leongunianellen@gmail.com

## TDP File

*TDP File Upload (Not required)*

[https://drive.google.com/open?id=1Bm7sHhjDpiCd32TX3K-whX0iPRs9J5FW](https://drive.google.com/open?id=1Bm7sHhjDpiCd32TX3K-whX0iPRs9J5FW)

## Team Name

*What is your team's name?*

Righteousness

## League

*What league do you participate in?*

IR League

## Country

*Where are you from?*

Macau

## Contact

*If other teams have questions about your robot, now or in the future, what email address(es) can we publish along with this document for people to reach you?

(You can put in multiple email addresses, like multiple team members, an email for the whole team or both. Feel free to share other ways of communication like Discord handles)*

leongunianellen@gmail.com

## Social Media

*Team Social Media Links (if you have any)*

https://www.youtube.com/@PCMS-rcjsoccer

## Team Photo

*Upload a photo of your whole team with your mentor and robots

Note: This is not mandatory and will be published along with your TDP if you choose to upload something*



## Members & Roles

*What are the names of the team members and their role(s)?*

Yogo: PCB & electronics design, defender state machine algorithms.
Terris: base control, and attacker chase/capture algorithms.
Anson: 3D modeling, hardware assembly/soldering, defender strategy.

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

60 minutes once per week

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

School Physics Lab

## Start Date

*When did your team start working on this year's robot?*

2025-Sep-05.

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

RobotCupJunior Singapore Open 2025: Lightweight League
RobotCupJunior China Open 2025: Lightweight League, Open League
China robot competition 2025 : Lightweight League
RobotCupJunior Japan Open 2026 Aichi: Lightweight League
RobotCupJunior China Open(Hong Kong) 2026: Lightweight League
RobotCupJunior China Open 2026: Lightweight League

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

Atructuring complex issues, teaching systematic debugging, and showing us how to effectively prompt AI tools for independent problem-solving.

## Workload Management

*How did you manage the workload?*

We communicated daily via WeChat and Discord, using a shared Google Sheet to delegate tasks, track progress, and ensure team alignment.

## AI Tools

*Which AI tools did you use?*

Chat GPT 5.5 pro；Gemini；Perplexity.

## Robot1 Overall

*Robot 1 Overall View*

![](images/18u8oJdNXtWsj9dX2oH9DdR1N5YbGy5Ts.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/1BCUZc5DzakmaK0xFo-FGwhGwRJhFTWRH.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1Ed9oluHe0emcqWfNdaRweiMwJDV4nY8x.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/1fbY8ATOj4PVIJmgDhiX0u8IifIciBy5J.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1HU6dzI7E4o0gw43WGE3hJzIUDjByh_qS.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/1US0IYfjvu69l8Bn5Px5k2rlztocu-D63.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/1mtldSiJyOf66v5pHO-PbsJe0DcMv7iAD.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/1p-qHO_ZhpheXZojCJESsrPDES3Q3RjUR.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/1yjnQP5LGJkQM2GuIfkHPYK7_0OL-u9xp.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/1VZw3D3CccJILvz8BxTzOOnAB2fctWaqb.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/1lbIbWKLU8QvrJJFhdHl-24uvnzPT698q.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/1sTw9VTkdPp-Y9o4dROnTaTpsWl3P9dLB.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1oTUhX0IqlP5qWnOIz7GY-VAJaFOmU8Sv.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1jH4pKusml2OwlsmfCwBtjzDhGEyVVQ29.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

We used AutoCAD/CorelDRAW and Onshape/Fusion 360. The chassis was designed around our Maxon motors for a low center of gravity and 3D-printed in ASA for impact and heat resistance.
Initially, the robot exceeded the 1.5kg limit and flexed under stress. We resolved this by cutting weight-saving pockets and adding reinforcing ribs in CAD. For printing, we optimized slicer settings with thicker outer walls, lower infill, and adjusted print orientation to maximize structural strength.

## Build Method

*How did you build your design?*

We 3D-printed our ASA chassis. We outsourced PCBs, CNC couplings, and sheet metal brackets to JLCPCB. To resolve ASA thermal shrinkage during assembly, we adjusted CAD offsets and hole clearances for a perfect fit.

## Motors & Reason

*How many motors have you used and why?*

Our 4-motor holonomic drive uses Maxon RE16 DC motors for rapid, omnidirectional X/Y translation and rotation. For optimal RoboCup carpet grip, we engineered custom omni-wheels featuring a rigid stainless steel hub (lowering the CG) and 17 sub-rollers fitted with nitrile rubber bands. This ensures high traction and durability during aggressive maneuvers. Full specs are in our BOM.

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

We engineered a kicker using an EML-1039B solenoid and a custom Fusion 360 striking plate. It features an ultra-low clearance for the new standardized ball. The wide plate geometry maximizes contact area, ensuring a highly stable, powerful transfer of kinetic energy.

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*

The system is driven by a high-torque T-Motor V2306 V2 (KV2400) paired with a 30A ESC. It features a split-mechanism design that utilizes lateral tension springs to generate dynamic, constant downward pressure, effectively locking the ball against the chassis during aggressive rotations.

## CAD Files

*CAD design files*

https://github.com/Ellenleong/2025-26-RCJ-Soccer-IR-PCMS/tree/main/Hardware/Airframe%20design%20CAD%20file

## Mechanical Innovation

*Mechanical Innovation*

Our key mechanical innovation is the active dribbler system. Initially, we utilized a static-height mount, but testing showed the ball easily escaped during rapid movement. Realizing the need for dynamic downward pressure, we engineered a spring-loaded, split-assembly design. A fixed base connects to a pivoting upper unit via springs. This mechanism actively presses downward, creating a continuous reactive force that securely locks the ball in place during aggressive maneuvers.

## Mechanical Photos

*Photos of your mechanical designs highlights*

![](images/1vW3zdWgmAPyNe68R93BgxP-QR6MLX8ai.jpg)
![](images/19wL3pj1C0iY9q19p0TMIoWbCIQvL0mbr.jpg)
![](images/1og7wWwqttoYZipQAZ5KEa2lgs7y0d4WD.jpg)
![](images/1fnaj4CqBjzeN92-tGkqLeiEHdz9dcuz4.jpg)

## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

[https://drive.google.com/open?id=1crdXkA884IAyRdC6StBEAyqbt_iha6gI](https://drive.google.com/open?id=1crdXkA884IAyRdC6StBEAyqbt_iha6gI)

## Power Circuit

*How does your power circuits work?*

Our JLCPCB mainboard splits a 3S 2200mAh 30C LiPo into 3 isolated domains: raw 12.6V for Maxon motors, a 3.3V/5A buck for Teensy 4.1 logic, and an isolated 48V boost for the EML-1040B kicker. This prevents brownouts and strictly meets RCJ 2026 safety limits.

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

To drive four Maxon RE16s, we use two WAYNESTARK V3.0 modules powered by 12.6V. A Teensy 4.1 sends 3.3V PWM signals for precise H-bridge speed control. These robust modules provide extreme thermal headroom and safely isolate sensitive logic from motor back-EMF spikes.

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

Our 3-MCU distributed architecture ensures parallel execution without bottlenecks. A Teensy 4.0 processes heavy camera/IR data into directional vectors. A compact ESP32-S3 handles line detection, ensuring zero-latency boundary braking. Finally, a 600MHz Teensy 4.1 acts as the central hub. Freed from sensor polling, its abundant I/O handles high-level game logic, holonomic kinematics, and precise PWM control for our four Maxon motors.

## Motor Control

*How do you use your processor to move your motors?*

The Teensy 4.1 uses inverse kinematics to translate X/Y/Theta vectors into motor speeds. A closed-loop PID reads encoders to dynamically correct speed errors. Corrected 3.3V PWM signals are then amplified by WAYNESTARK V3.0 drivers to regulate 12.6V motor power for precise holonomic movement.

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

Our dual-sensor system combines IR and vision. 12 radial TSOP4038 receivers detect IR signals, with a low-pass filter converting pulses to analog voltages. An ESP32-S3 multiplexes this data to a Teensy 4.0 via UART. Simultaneously, four MaixCam Lites (GC4653, 145° lenses) send visual data over UART. The Teensy 4.0 aggregates both streams, forwarding integrated results to the main controller for decision-making.

## Line Detection

*How does your line detection circuits work?*

Our custom Line Sensor PCB detects white lines using 30 NJL7502 sensors and 30 white LEDs spaced at 12mm. Two 16-channel multiplexers optimize pin usage. A Xiao ESP32-S3 processes this data and transmits computed line positions to the Teensy 4.1 via UART.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

The Teensy 4.1 reads four analog ultrasonic sensors via ADC for obstacle avoidance. It also uses a BNO055 IMU via I2C for precise heading control. For localization, four MaixCam Lite cameras detect the goal's angle and distance, allowing the robot to estimate its relative field position.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

To maximize kick power, we use a 12V 35N electromagnet powered by a 48V/2A boost module and two 2.2mF capacitors. We solved inrush current shutdowns by adding a 47Ω resistor. A Teensy 4.1 uses dual optocouplers to safely control P-channel and N-channel MOSFETs with a flyback diode.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*

To fix low startup torque, we upgraded the dribbler to a T-Motor V2306 (KV2400) and Hobbywing 30A ESC. To improve ball retention, we replaced the static-height mount with a spring-loaded pivot mechanism. This applies dynamic downward pressure to the silicone roller, actively securing the ball.

## Schematics

*Schematics of your robot*

[https://drive.google.com/open?id=1yoIZWHJOxymckcxFjpp4MGO8wUuoCOdB](https://drive.google.com/open?id=1yoIZWHJOxymckcxFjpp4MGO8wUuoCOdB)
[https://drive.google.com/open?id=1ZUToAKKtqeQ9Fp2O86506iiXCAl0H_m0](https://drive.google.com/open?id=1ZUToAKKtqeQ9Fp2O86506iiXCAl0H_m0)
[https://drive.google.com/open?id=1qTG8z49X4thi3-oKdh2dT50KQMoAVE0H](https://drive.google.com/open?id=1qTG8z49X4thi3-oKdh2dT50KQMoAVE0H)
[https://drive.google.com/open?id=1F9zbu5HIThZWIeoU5z0pTjkqb3d2BIye](https://drive.google.com/open?id=1F9zbu5HIThZWIeoU5z0pTjkqb3d2BIye)

## PCB

*PCB of your robot*

![](images/1Z03p1FaQEGMAM3c66FGu3g7-o2sUGYDY.png)
![](images/1MQqNX9nVXtWcjELP4P190q7uriUczABF.png)
![](images/1wvnFjt2gVxvMELH20m7GEi2W2jrOjmfX.png)

## Electronics Innovation

*Electronics Innovations*

The electronic subsystem we are most proud of is our custom-engineered Top-Level Sensor Aggregation PCB, designed to provide flawless 360-degree environmental awareness while completely eliminating computational bottlenecks. To achieve comprehensive visual tracking without blind spots, we engineered a quad-camera array utilizing four Maix Cam Lite AI vision modules mounted strategically on the upper board. Processing four concurrent, high-framerate video streams would paralyze a standard microcontroller, so we routed these cameras into a dedicated Teensy 4.0. This processor acts purely as a vision aggregator, synthesizing the four discrete fields of view into unified, prioritized targeting vectors. Complementing this vision system is our proprietary infrared tracking ring, which consists of 12 TSOP4038 IR receivers uniformly distributed around the PCB's perimeter. The critical hardware innovation in this circuit was the integration of custom Low-Pass Filters (LPF) on the sensor output lines. In chaotic tournament environments, high-frequency electrical noise and erratic ambient light interference frequently cause false-positive sensor triggers. By implementing these analog RC filters, we successfully smoothed the signal envelopes, delivering pristine, noise-free data to a dedicated Seeeduino XIAO ESP32-S3 coprocessor. The ESP32-S3 rapidly polls all 12 sensors and runs a continuous trigonometric algorithm to calculate the precise angle and relative distance of the infrared ball. Finally, both the Teensy 4.0 and the ESP32-S3 act as localized sensory brains, streaming only their finalized, highly accurate coordinate data down to the main Teensy 4.1 motor controller via high-speed serial. This advanced distributed architecture guarantees that our robot's main logic loop receives instantaneous, deeply filtered telemetry without ever having to pause motor execution to process raw sensor data.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1FZ2N1WX9lSJo6kqEeoXUM6SCNZ7iCGex.jpg)
![](images/1_HLdENtF6UfICW9gL-MhVVjmAvkAOuFl.jpg)
![](images/1cWvHBqIur8R4M3BNkKUZF9IBfhOIakDo.jpg)
![](images/1IgoCbi5nmhKxVt8iKSRAYspqSDyCIVPR.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

Our system fuses IR and camera data (Teensy 4.0 & ESP32-S3). For near-field, an EMA filter and Top-5 Vector Synthesis process IR signals, yielding a 1-degree trajectory. For far-field, cameras track the ball, goal, and lines for absolute spatial localization. Fusing these streams pinpoints the ball's global coordinates, enabling optimized navigation and responsive control.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

Our attacker uses a blended chase algorithm to smoothly wrap around the ball, avoiding collisions. It combines a tangent calculation for orbiting at wide angles and a PD controller for precise, overshoot-free frontal interception. A dynamic factor seamlessly shifts between these paths based on alignment, while pursuit speed dynamically scales up to 1.5x based on distance.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

Our sensor fusion integrates camera and ultrasonic data for precise (x,y) field localization. To refine pose estimation, a BNO055 IMU provides real-time yaw compensation, mitigating rotational drift during aggressive turns. This highly stable spatial awareness drives our high-level control logic, enabling the robot to partition tactical zones and execute position-dependent strategies.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

For robust boundary retention, our vector-based line avoidance algorithm uses a radial sensor array. Binarized analog telemetry detects the white line. Detections map to geometric coordinates and fuse via vector superposition, yielding a resultant vector for proximity. Contiguous triggers form a stable normal vector; fragmented detections use spatial clustering for a reliable escape trajectory.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

Our state machine drives offense. Without the ball, the robot centers. Upon detection, it intercepts and engages the active dribbler. In the defensive half, it shields the ball with its chassis and navigates the outer edge to bypass center traffic. In the offensive half, it pivots, uses vision to target the largest unguarded gap, and fires the 48V EML-1040B kicker for a precise shot.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

Our defensive state machine fuses ultrasonic and vision data for precise localization, shifting between central fallback, PID center defense, and lateral tracking. To counter impacts, it monitors absolute heading for immediate PID yaw corrections. For boundary retention, the NJL7502L array calculates a repulsive normal vector to keep the robot in the goal zone and prevent out-of-bounds penalties.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

While inter-robot communication is advantageous, our current models operate independently. Due to limited testing time this season, we prioritized core mechanical reliability and single-agent algorithms. Looking ahead, we plan to implement Radio Frequency (RF) modules for robot communication. This will enable dynamic role assignment, prevent double-targeting, and execute collaborative plays.

## Software Innovation

*Software Innovations*

Our ChaseBall Algorithm resolves overshooting via four elements:
PD Control: Angle error drives Kp alignment and Kd damping for stable interceptions.
Tangent Path: Calculates a curved orbital approach to avoid collisions.
Blending: Shifts between PD (narrow angles) and Tangent (wide angles) based on the ball's angle.
Speed: Scales up to 1.5x for distance, slowing for close-quarter control.
This dynamic fusion ensures faster acquisition and precise offensive positioning.

## GitHub Link

*GitHub link*

https://github.com/Ellenleong/2025-26-RCJ-Soccer-IR-PCMS/tree/main/Software

## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=1WTI39QXNkL2QfUANQq0pjnek8y-LfQPz](https://drive.google.com/open?id=1WTI39QXNkL2QfUANQq0pjnek8y-LfQPz)

## Cost

*How much did it cost you to build your robots?*

• Robot Unit Cost: $1,468.45 USD 
• R&D & Testing Cost (including trial and error): $3,700 USD
• Environmental Cost (venue and balls): $210 USD 
Total Project Cost: $5,510 USD
Conversions are based on the exchange rate of 1 CNY = 0.15 USD.

## Funding

*How did you gathered the funds to build the robots?*

• 12% Sponsor (Maxon): Motor discount
• 88% School: Remaining costs

## Affordability

*How affordable was it to compete in RoboCupJunior Soccer?*

4

## Answer Check

*Have you checked all of your answers?*

Yes!

## Publication Consent

*We publish TDPs and posters during or after the competition as described in the beginning*

Yes, we acknowledge everything submitted in the above form can be published.

