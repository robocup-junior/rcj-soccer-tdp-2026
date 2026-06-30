## Timestamp

*Tijdstempel*

28-6-2026 15:58:32

## Email Address

*E-mailadres*

kushals@vasantvalley.edu.in

## TDP File

*TDP File Upload (Not required)*



## Team Name

*What is your team's name?*

VVS Ballers

## League

*What league do you participate in?*

IR League

## Country

*Where are you from?*

India

## Contact

*If other teams have questions about your robot, now or in the future, what email address(es) can we publish along with this document for people to reach you?

(You can put in multiple email addresses, like multiple team members, an email for the whole team or both. Feel free to share other ways of communication like Discord handles)*

Team email ID - vvsballers@gmail.com
Kushal Sachdeva - kushal.sach78@gmail.com

## Social Media

*Team Social Media Links (if you have any)*

www.instagram.com/vvs_ballers

## Team Photo

*Upload a photo of your whole team with your mentor and robots

Note: This is not mandatory and will be published along with your TDP if you choose to upload something*

![](images/1et-e2eoS_cgPzMYgTaTpbt7qLZm_do0m.jpg)

## Members & Roles

*What are the names of the team members and their role(s)?*

Kushal Sachdeva (Team Leader) — Electrical, Software & CAD Engineer
Darsh Goel — Mechanical & CAD Engineer

## Meeting Frequency

*How often did your team meet?
(e.g. 90 minutes once per week or a day every weekend.)*

8–10 hours/day from 7–27 June; 4 hours/day from February to May

## Meeting Place

*Where did you meet to work on your robot?
(e.g. a robotics room at school, at some other place, one of your homes, school library etc.)*

A robotics room set up at one of our homes

## Start Date

*When did your team start working on this year's robot?*

February 2026

## Past Competitions

*Which RoboCupJunior competitions have you competed in and in which leagues?*

2023–24 Season
	•	RoboCup Regionals – Best Innovation Award (qualified to Nationals)
	•	RoboCup Nationals – Best Robot Design Award (qualified to Asia-Pacific)

2024–25 Season
	•	RoboCup Regionals – 3rd Place (qualified to Nationals)
	•	RoboCup Nationals – 3rd Place (qualified to Internationals)
	•	RoboCup Internationals, Brazil – Top 20 worldwide

2025-26 Season
	•	RoboCup Regionals – Best Innovation Award (qualified to Nationals)
	•	RoboCup Nationals – 1st Place (qualified to Internationals)

## Mentor Contribution

*Which parts of your work received the most contribution from your mentor?*

External Nano caps motor-driver current (overheating); bulk cap stopped Ultrasonic PCB resets; IR smoothing + camera fixed IR's short range.

## Workload Management

*How did you manage the workload?*

We planned in Notion (every task assigned per member with a deadline), shared all PCB, 3D-design and code files on Google Drive, and ran a WhatsApp group for daily task lists and progress updates.

## AI Tools

*Which AI tools did you use?*

We used Claude's Fusion 360 MCP to help design the supporting beams that hold the IR sensor, and to help lay out the Power PCB and Ultrasonic PCB

## Robot1 Overall

*Robot 1 Overall View*

![](images/1Dwe-Wk0ZSLAvEOqQsEt1MmUmRG2Z9iSR.jpg)

## Robot1 Front

*Robot 1 Front view*

![](images/1A1l0wiSSo1W4_28ZJacxt8J7TPhwYL1m.jpg)

## Robot1 Back

*Robot 1 Back view*

![](images/1wBWeqmcZwGWSCMnEIKWyFaURA_3rwJuK.jpg)

## Robot1 Top

*Robot 1 Top View*

![](images/15Xm3W8gnbx0--rB5taf2Uw4fhFM-wqG1.jpg)

## Robot1 Bottom

*Robot 1 Bottom View*

![](images/1acHBGTINDSgnG2KxM8bw63dxfsLxD2UK.jpg)

## Robot1 Right

*Robot 1 Right View*

![](images/1DYipzFhQTdJTrOdYpF-ilVxyAYrwrVrq.jpg)

## Robot1 Left

*Robot 1 Left View*

![](images/1N0XcJyqTAGena5LsCBDQobO2IkQpNdYS.jpg)

## Robot2 Overall

*Robot 2 Overall View*

![](images/1m8wIPLW1Gxk2ThhgTJczbn3YijmzsS7N.jpg)

## Robot2 Front

*Robot 2 Front view*

![](images/1v6BTOxfOQcB2hv-duKwuGI5X5q3VitXh.jpg)

## Robot2 Back

*Robot 2 Back view*

![](images/1EsDVHFyJ-cnTFnjMR_dnlVvvLCYInDuw.jpg)

## Robot2 Top

*Robot 2 Top View*

![](images/1RFQbR3258Oz-IZOtc2lTfZzHKkNw-M9I.jpg)

## Robot2 Bottom

*Robot 2 Bottom View*

![](images/124iGRvWIY6pjl-KeH_KFtLLlS-W5COhS.jpg)

## Robot2 Right

*Robot 2 Right View*

![](images/1i5Q2AmDLLo9FpCBsK24pG6iW5ZAQwpTC.jpg)

## Robot2 Left

*Robot 2 Left View*

![](images/1E3T1Qk0xOzSAp53H-m5nghan5MQmkmvW.jpg)

## Mechanical Design

*How did you design the mechanical parts of your robots?*

Designed in Fusion 360 from hand sketches. With our physics teacher we compared 3- vs 4-omni-wheel layouts, wheel diameters and sensor placement within the 22 cm / 1.5 kg IR-league limits; the 4-wheel diamond won for holonomic agility and even traction. To improve it we added a 3D-printed support-beam frame that keeps the IR ring rigid and planar, sized the capture mouth to the 1.5 cm ball-zone limit, and packed the five PCBs into a compact stack.

## Build Method

*How did you build your design?*

PCBs were made by JLCPCB; parts were 3D-printed on a Bambu Lab printer in PETG (TPU for grip). We tuned print tolerances, reamed the IR-cover holes to 3.2 mm, and reshaped the support beams to clear the Power-PCB terminals and Teensy USB.

## Motors & Reason

*How many motors have you used and why?*

4 motors, one per omni wheel in a diamond (Pololu 20D mm 12 V gearmotors). Four wheels give true holonomic motion - the robot drives straight at the ball from any bearing while the gyro holds heading - and spread force evenly for pushing duels. We 3D-printed our own omni wheels (PETG hubs + TPU rollers) so the diameter, roller count and grip fit our chassis and the smaller ball.

## Kicker Design

*If your robot has a kicker, explain how you designed and built the mechanics of the kicker*

A solenoid kicker in the capture mouth. The 3D-printed capture area cradles the ball within the 1.5 cm zone; a solenoid plunger strikes the ball forward. A printed mount and coupling align the plunger to the ball centre, and the kick only fires once the capture HC-SR04 confirms the ball is seated.

## Dribbler Design

*If your robot has a dribbler, explain how you designed and built the mechanics of the dribbler.*

N/A

## CAD Files

*CAD design files*

https://github.com/Kushal-Sachdeva78/VVS-Ballers-RoboCup/tree/main/RoboCup%20Internationals%202025-26/CAD

## Mechanical Innovation

*Mechanical Innovation*

Our proudest part is the fully self-designed, 3D-printed omni wheels. No off-the-shelf wheel fit our size limit or the smaller 2026 ball, so we built our own: PETG hubs with TPU-gripped rollers, refined over three print rounds to dial in roller diameter, count, grip and concentricity for smooth, slip-free holonomic motion. 
Second: a printed support-beam structure that ties the Main, IR-cover and ultrasonic boards into one rigid stack so the IR ring stays planar and aligned through collisions.

## Mechanical Photos

*Photos of your mechanical designs highlights*

![](images/1SE4V6UfIkVBigxFJZM20j-GuCK1gXa-8.jpg)
![](images/1hbQVwospwCFmTZvB2ZdZas_owbgQJlnG.jpg)
![](images/13VYgTnZNH7swpEOACXdXlKxCM0bs5E1o.jpg)
![](images/1FpO9Wcu9zPLl13PAl1qUQcn6rHEb40G-.jpg)
![](images/1yF2vItl0zoM4LIrCjmNuikqoBdpgQwuD.jpg)

## Electronics Block Diagram

*Provide us with a block diagram of your robot's electronics*

![](images/19SoWQb5kala3jYdOdTdjUatmPVdWrGcz.png)

## Power Circuit

*How does your power circuits work?*

A 12 V LiPo pack feeds a Power PCB which generates: 5 V (buck) for the Teensy boards boards and the OpenMV camera; 3.3 V (buck) for sensor logic; and 48 V (boost) for the solenoid kicker (All this is done on one PCB). The 12 V rail goes directly to the motor drivers. Bulk capacitors sit on each rail

## Motor Drive Circuit

*How do you drive your motors? Explain the circuits you use for that*

Each omni wheel has its own DRV8263H brushed driver (12 V power, 3.3 V logic, PH/EN mode); the Main Teensy feeds each a direction + PWM pin. Each driver's IPROPI current output goes to an Arduino Nano that pulls DRVOFF to coast a motor over ~1 A (stall ~1.6 A), preventing stall overheating.

## Microcontroller & Reason

*What kind of micro controller or board do you use for your robot? Why did you decide to use this part for your robot? If you have more than 1 processor, explain each one separately.*

3× Teensy 4.1:
(1) Main board: chosen for its 600 MHz speed and many hardware UARTs (it must service 5 serial links + the comms module at 100 Hz).
(2) IR ring board: needs to read 16 analog channels fast with on-chip averaging; 
(3) Line ring board: reads 18 analog channels at >500 Hz. 2×

Arduino Nano Every:
(4) Ultrasonic board: Receives values from 4 HC-SR04s; 
(5) Motor-current limiter: Current protection runs independently of the main code. 

Plus the OpenMV H7 as a vision coprocessor.

## Motor Control

*How do you use your processor to move your motors?*

The main Teensy 4.1 PWMs four DRV8263H drivers (one direction pin + one analogWrite PWM pin each, shared SLEEP, 12 V). It mixes a translation pattern with a gyro heading-correction term, so it strafes any direction while facing forward. A separate Nano caps current via IPROPI/DRVOFF.

## Ball Detection

*How does your ball detection sensors and/or camera[s] work?*

A 16-channel TSSP58038 IR receiver ring is the primary ball sensor - the IR-league ball emits IR, and each receiver's reading becomes an intensity (baseline - raw). An OpenMV H7 camera complements it: besides finding the goal, keeper and open-corner aim, it also detects the orange ball, letting us cross-check and reconfirm the IR ring's bearing - camera+IR fusion that helps at short range where the IR ring alone struggled. The camera sends its data to the main board as a 11-byte frame.

## Line Detection

*How does your line detection circuits work?*

A dedicated Line PCB carries four QTR-MD-05A IR-reflectance arrays - 18 sensors facing the floor on all sides. The white field line reflects differently from the green carpet (white reads low), and a board flags 'line' when >=2 of its channels cross threshold. The four ultrasonics range the walls.

## Navigation/Position Sensors

*What sensors do you use for navigation and how are these sensors connected to your processor? What sensors do you use to find your position in the field? What about the direction your robot faces?*

Direction: a BNO055 9-DOF IMU on the main board (I2C/Wire2, address 0x28) in IMUPLUS mode, so the drifting magnetometer is ignored and gyro+accel give a stable heading for the 100 Hz hold-PID. Position: four HC-SR04 ultrasonics, one per side, wired to the ultrasonic Nano that streams their distances to the main board for boundary and goal standoff.

## Kicker Circuit

*How do you drive your kicker system? How does the circuit make the kicker work?*

A relay module (IN1 = pin 22, active-HIGH) switches the 48 V solenoid; a capture HC-SR04 over the mouth (TRIG 20 / ECHO 21) confirms the ball before firing. Firmware safety: 2-sample capture debounce, a fixed 500 ms pulse, 1.5 s cooldown, a hard 600 ms max-on cutoff, and a boot-safe relay state.

## Dribbler Circuit

*How does your dribbler system work? What components and circuits did you use to drive it?*

N/A

## Schematics

*Schematics of your robot*

![](images/1OBpdmuanlQ-ROSyKPatmY7FOcVb6SybA.png)
![](images/1Do0kacbtN5gZYyPwgEOT9xUpfMoYNinl.png)
![](images/1al16sV8sHLso898lwHnWcO4zJFfIpGch.png)
![](images/1CMN8rXRXMtcP1XeQ5_bFOGPzMlahUDsy.png)
![](images/1dLymVPHc_fiuyx36ddyj-pQhgIdC-Aob.png)

## PCB

*PCB of your robot*

![](images/1SXcTnmQWie2fWxOLrACKkcnshU2gqQx6.png)
![](images/1GMMAaLhWcPJIyRNr-P4wzL2rxAzrep5X.png)
![](images/1MysmFRe-spOt9Kb-iIgEA4tHZa6-BRPA.png)
![](images/14zcLvoaRN3jAmnmBkxQ7zG8mk__YldNz.png)
![](images/1uwi7mwHsrtfBfQCLxgnwndFEcj9w6fqX.png)

## Electronics Innovation

*Electronics Innovations*

Our federated multi-PCB architecture: three purpose-built boards talk over CRC-8-framed UART, so a glitch on any wire is rejected, not acted on. We are proudest of three boards. The Power PCB is compact yet generates and distributes four rails (12 V, 5 V, 3.3 V, 48 V) cleanly and continuously across the whole robot from one battery. The IR PCB gives each of its 16 receivers its own RC filter, smoothing the pulsed IR into a clean analog level the Teensy reads as a precise bearing. The Main PCB integrates everything on one board - it takes data from every sensor link, runs the heading PID, drives all four motors, and carries the BNO055 IMU and the solenoid kicker at once.

## Circuit Photos

*Photo of your circuit boards highlights*

![](images/1dcjKMdUlGvhBQD2kLsoF3I5zIi7FjT6s.jpg)
![](images/1iMOrM0Mr7Z2GVVqI6I8-6FAk8z1IJlwq.jpg)
![](images/1EGeiC59zICI9d4xAA6CtVDJo7lcAc-L_.jpg)
![](images/10MASUQR47ySVgoRAC2GYVsa0Cl-Q4mE5.jpg)
![](images/1rLASx-xYrZehlHQbcfr297KbVhY2nDol.jpg)

## Ball Detection Method

*How do you find where the ball is? How do you read the data from the ball detection sensors and/or camera?*

The IR board reads all 16 channels, converts each to intensity = baseline - raw, rejects ambient and damps lone spikes. It then takes an intensity-weighted vector sum (atan2 over all lit sensors) for a smooth bearing, with hysteresis (60/35) and EWMA smoothing, and sends <dir>a<dist>b (500 = no ball) to the main board. The camera is read as an 11-byte frame; stale links (>200 ms) are ignored.

## Ball Catch Algorithm

*How does your algorithm work to catch the ball? Is there a difference between your robots in how they move towards the ball? Explain the differences.*

Attacker: it sorts the IR bearing into a drive sector and translates straight at the ball (speed 250) while the gyro holds heading; on capture it switches to aim-and-kick. 

Defender: it does not chase up-field - it stays on its goal line and runs a lateral PID on the ball's bearing to keep its body between ball and goal, with an intercept boost when the bearing moves fast, clearing on contact.

## Positioning Algorithm

*How do you use your sensors in your algorithm to find your position inside the field and how do you use that position to move your robots around?*

The four ultrasonics are used reactively (no x/y estimate), each giving its wall distance. The attacker uses them with the line ring to flee field edges; the defender centres in the mouth from the left/right difference and holds a set distance-range from its own goal via the back sensor. Drive is holonomic: a translation vector plus the heading-PID correction, normalised so no wheel saturates.

## Line Algorithm

*How does your robot find the lines to stay inside the field? What algorithms do you use to avoid going out of bounds?*

Walls are sensed by ultrasonics, the white boundary by four QTR-MD-05A reflectance arrays (>=2 white channels = line). Attacker: a side is the edge only when its ultrasonic reads <300 mm AND that side sees white, debounced 3 passes; it then flees, never on a stale link. This two-of-two rule stops a false reading triggering an out-of-bounds penalty. Defender: the line keeps it on the goal edge.

## Goal Algorithm

*What algorithms do you use to score goals? How do you use your kicker and dribbler to handle the ball?*

The camera finds the goal and keeper and returns the open-corner bearing. On capture (mouth HC-SR04 <45 mm, 2 samples) the attacker holds heading, then spins in place until the open corner is within 5 deg ahead, and only then fires the 48 V solenoid (500 ms pulse, 1.5 s cooldown, 600 ms hard cutoff). The defender uses the same kicker for a short clearing kick. No dribbler.

## Defense Algorithm

*What algorithms do you use to avoid the opponent team scoring? How do your robots defend your own goal?*

The defender's Defender_Full runs GUARD (centre on the line, hold standoff) → TRACK (lateral-PID onto the ball, intercept boost) → CLEAR (push/kick the ball away on contact) → RECOVER (re-home to the line). A back-wall safety rule forbids reversing toward its own goal when the rear wall is < 90 mm, so a bad reading can't drive it into its own net.

## Robot Communication

*Do your robots communicate with each other? How do you use this communication to your advantage?*

Yes - the robots share status over a 2.4 GHz link (the only band RCJ permits for inter-robot comms). We use it for automatic role-switching: if one robot drops off the link (fouled, penalised or removed), its partner switches from attacker to defender so our goal is never left open while we are a robot down; they resume normal roles when it returns at kick-off.

## Software Innovation

*Software Innovations*

Both are about clean data from cheap sensors.

(1) Ultrasonic smoothing: we ping opposite sensors together to kill cross-talk, temperature-compensate distance, run a per-sensor median-of-3, and coast over dropouts so a missed echo never blinks a wall away.

(2) IR tracking: instead of strongest-sensor, we sum intensity-weighted vectors over all lit receivers (atan2) with hysteresis and spike damping, for a smooth bearing on the small fast ball. Both feed our fused line+ultrasonic boundary escape

## GitHub Link

*GitHub link*

https://github.com/Kushal-Sachdeva78/VVS-Ballers-RoboCup/tree/main/RoboCup%20Internationals%202025-26/Firmware

## BOM

*Bill of Materials (BOM)*

[https://drive.google.com/open?id=1EPaQ7X6d3vpanGlAbN6bnXVHUaxpJ8NOUNK7xiksze4](https://drive.google.com/open?id=1EPaQ7X6d3vpanGlAbN6bnXVHUaxpJ8NOUNK7xiksze4)

## Cost

*How much did it cost you to build your robots?*

Robots (cost of components that are in your robots right now): 600 Euro each
Experiments (failed builds, broken hardware etc.): 1200 Euro
Spare Parts (spare motor drivers, sensors, fuses, PCBs, etc.): 1000 Euro
Environment (fields, balls, 3D printer, soldering station, power tools, etc.) : 1100 Euro

## Funding

*How did you gathered the funds to build the robots?*

50% Sponsors 
0% School
50% Parents

## Affordability

*How affordable was it to compete in RoboCupJunior Soccer?*

4

## Answer Check

*Have you checked all of your answers?*

Yes!

## Publication Consent

*We publish TDPs and posters during or after the competition as described in the beginning*

Yes, we acknowledge everything submitted in the above form can be published.

