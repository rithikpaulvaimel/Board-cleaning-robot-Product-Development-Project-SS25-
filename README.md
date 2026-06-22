# Automated Board Cleaning Device-Product Development Project SS25
This repository documents the Product Development Project (IBE, Summer Semester 2025) conducted at Technische Hochschule Würzburg-Schweinfurt (THWS).

As part of a team of five students, we designed and developed an automated board-cleaning device for whiteboards and blackboards. The project focused on product development, mechanical design, component selection, CAD modelling, prototyping, and technical validation.

----
## Motivation
Whiteboards and blackboards remain widely used in educational and professional environments, yet cleaning them is still a repetitive manual task. The objective of this project was to develop a compact, portable, and user-friendly device capable of automating the cleaning process while minimizing user effort and improving efficiency.

The final solution was developed through a structured engineering design process involving requirement analysis, concept generation, evaluation of multiple design variants, risk assessment (FMEA), and prototype development.

## Project Workflow

The project was carried out using a structured product development approach, progressing from planning and research to concept development and prototyping.

### 1. Project Planning & Team Organisation
- Defined team roles and responsibilities.
- Developed the LOP, RSI Matrix, Meeting Minutes template, and Gantt Chart.
- Established project milestones and deadlines.

### 2. Technical & Market Research
- Investigated existing board-cleaning solutions.
- Analysed market requirements and technical feasibility.

### 3. Requirements Engineering
- Developed the List of Requirements (LOR).
- Defined functional, technical, and customer requirements.

### 4. Black Box Analysis & Functional Structure Development
- Created the Black Box Model.
- Developed the Function Structure and identified key sub-functions.

### 5. Morphological Box 
- Constructed a Morphological Box to identify alternative technical solutions.
- Generated multiple concepts for each product function.

### 6. Concept Development & Evaluation
- Each team member developed an individual design variant.
- Evaluated all concepts against both technical and economic perspectives.
- Selected the most promising solution and developed an optimized variant.

### 7. Concept Optimization & Technical Validation
- Refined the selected concept.
- Developed detailed CAD models, technical drawings, and system architecture.
- Performed engineering calculations, technical proofs, cost estimation, and FMEA analysis.

### 8. Prototype Development
- Built and tested a functional prototype.
- Validated key product functions and design assumptions.

### 9. Future Improvements
- Potential improvements that could be implemented in future versions of the prototype.

## Technical & Market Research

Before concept development, a technical and market analysis was conducted to understand existing solutions, market opportunities, relevant technologies, regulations, and intellectual property considerations.

### Research Areas

#### Market Analysis
- Investigated the global whiteboard, blackboard, and interactive board markets.
- Identified education and corporate environments as the primary target sectors.
- Evaluated trends in classroom automation and smart board adoption.

#### Competitor Analysis
The following categories of competitors were analysed:

**Direct Competitors**
- Scribit
- iBoardBot
- Joto
- SwiperWHITE
- AxiDraw

**Indirect Competitors**
- Smart Boards
- Virtual Collaboration Whiteboards (Miro, Microsoft Whiteboard, Lucidpark)
- AR/VR Projection Whiteboards

#### Technology Review
Evaluated potential technologies required for implementation, including:
- Rail-guide systems
- Wheel-based motion systems
- Stepper and servo motors
- Sensor systems
- Microcontrollers
- Cleaning and writing mechanisms
- Battery-powered operation

#### Patent Search
A comprehensive patent search was conducted to identify existing solutions and ensure design originality. Particular attention was given to:
- Magnetic attachment systems
- Vacuum attachment systems
- Track-mounted cleaning mechanisms
- Automated writing and erasing devices

#### Standards & Regulations
Relevant regulations and standards were reviewed, including:
- CE Marking
- RoHS Directive
- WEEE Directive
- Low Voltage Directive (LVD)
- Electromagnetic Compatibility (EMC)

### Key Findings
- Existing products typically focus on either writing or cleaning, but rarely both.
- Many solutions require permanent installation or external power supplies.
- Magnetic attachment offers a practical solution for most modern boards.
- There is an opportunity for a portable, battery-powered device that combines automation with ease of use.

## List of Requirements (LOR)

The List of Requirements (LOR) was developed to define the functional, technical, safety, sustainability, and project constraints of the device. The requirements were initially established based on customer expectations and were later refined using insights from the Black Box Model, Function Structure, and Morphological Box.

The finalized LOR served as the foundation for concept generation, evaluation, and design decisions throughout the product development process, ensuring that the final solution aligned with both customer needs and technical objectives.

<img width="577" height="732" alt="image" src="https://github.com/user-attachments/assets/1f12ab89-3380-4126-b72c-0fbf161d5df0" />
<img width="577" height="203" alt="image" src="https://github.com/user-attachments/assets/c971e2e5-e8dc-4d67-a6c0-674f68ccabc2" />



### Key Requirements

The device was required to be portable, battery-powered, and capable of cleaning both whiteboards and blackboards. Key design objectives included full board coverage, a minimum runtime of 90 minutes, adjustable sizing for different board dimensions, safe operation, easy mounting, and compliance with relevant environmental and safety regulations. Additional requirements focused on sustainability, maintainability, user-friendly operation, and adherence to the project budget and timeline.

## Black Box Model 

To better understand the system and its interactions with the environment, a Black Box Model was developed. The model identifies the main function of the device, along with its inputs, outputs, and potential internal and external disturbances.

Based on the Black Box Model, a Function Structure was created to decompose the overall system into smaller functional elements. These functions were grouped into key areas such as user interaction, movement and navigation, power management, and the cleaning mechanism. This structured approach helped define the requirements for each subsystem and served as the foundation for concept generation and the development of the Morphological Box.

### Black Box Model

<img width="972" height="722" alt="image" src="https://github.com/user-attachments/assets/fb81ddf3-a206-4276-b280-9a52e8e1f7af" />

## Function Structure

Following the development of the Black Box Model, a Function Structure was created to decompose the overall system into smaller and more manageable functions. This process helped identify the key tasks required for the device to perform its primary objective: automatically cleaning whiteboards and blackboards.

### Main Function
- Automatically clean whiteboards and blackboards.

### Main Subfunctions

#### 1. User Interaction
Functions related to operating and monitoring the device.
- Receive user input (start/stop commands).
- Display device status (battery level, connectivity, operating state).
- Indicate operating status during cleaning.

#### 2. Movement & Navigation
Functions responsible for safe and effective movement across the board.
- Detect board boundaries.
- Guide the device across the board surface.
- Maintain secure attachment to the board.

#### 3. Power Management
Functions responsible for supplying and managing energy.
- Store energy using a rechargeable battery system.
- Provide power to motors, sensors, and control electronics.

#### 4. Cleaning Function
Functions directly related to the cleaning process.
- Activate the cleaning mechanism.
- Remove marker or chalk residue from the board surface.

The Function Structure provided the basis for the development of the Morphological Box, where alternative technical solutions were generated and evaluated for each subfunction.


## Morphological Box

The Morphological Box was developed using the identified subfunctions and possible technical solutions for each function. This method enabled the generation of multiple design concepts by combining different solution principles. 

<img width="1070" height="663" alt="image" src="https://github.com/user-attachments/assets/0bca56a7-01d9-4a35-807f-cd3e2cd2a2d9" />
<img width="992" height="542" alt="image" src="https://github.com/user-attachments/assets/7b7c0ad4-ba85-4d34-a6e2-40731a866167" />

**Note:**
- 🟢 Green = Solutions selected in my concept variant
- Other coloured dots = Solutions selected by other team members

## Initial Concept Variant (My Variant)

Using the Morphological Box, each team member developed an individual concept by selecting different technical solutions for the identified subfunctions.

The concept presented below represents the design variant I developed during the concept race phase. It focuses on portability, magnetic board attachment, sensor-assisted navigation, battery-powered operation, and an automated cleaning mechanism. 
### Concept Image 
<img width="637" height="372" alt="image" src="https://github.com/user-attachments/assets/313986fe-636c-4e8a-a67e-d94dff9aa08f" />
<img width="633" height="391" alt="image" src="https://github.com/user-attachments/assets/2c15370c-545d-42ea-a12d-2572ea7901dd" />
<img width="721" height="383" alt="image" src="https://github.com/user-attachments/assets/3df55a2f-e1ee-4dce-84c8-ba26ea8f84aa" />
<img width="660" height="472" alt="image" src="https://github.com/user-attachments/assets/bcbea02c-46f3-4bb0-b1eb-4c043781ae23" />

### Brief Overview
This concept variant was designed as an automated cleaning device for both whiteboards and blackboards. The system incorporates an LCD display for device status monitoring, including power status, battery level, and microfiber pad replacement reminders. Air vents and cooling fans were integrated to maintain safe operating temperatures.

The device uses four neodymium magnets for secure attachment to the board surface and four motor-driven wheels for movement along the X and Y axes. A detachable microfiber cleaning pad is mounted underneath the device and is designed with dedicated openings for the wheels and magnets. To prevent board damage, the wheel surfaces are coated with the same material as the cleaning pad.

Additional features include an optional solvent dispenser attachment, integrated carrying handles, and a push-button with LED indication for operation. Internally, the design consists of a 12V 4000mAh battery, ESP32 microcontroller, servo motors, stepper motors, temperature sensor, peristaltic pump, and buck converter. Cleaning fluid is distributed through a tubing system that ensures even wetting of the microfiber pad without dripping.

### Working Principle

#### Step 1 – Device Activation
- The user presses the push button located on the device.
- The LED indicator illuminates, confirming activation.
- The ESP32 and all connected components are powered on.
- Cooling fans remain inactive unless the temperature sensor detects overheating of the battery, motors, or ESP32.

<p align="center"><img width="892" height="422" alt="image" src="https://github.com/user-attachments/assets/ee7064e1-32e1-408d-8e4d-c981f009aebc" /></p>


#### Step 2 – Board Configuration
- The user connects to the ESP32 via Wi-Fi using a mobile application.
- The board height is entered into the application.
- This value is used to calculate the required vertical movement distance during cleaning.

<p align="center"><img width="837" height="500" alt="image" src="https://github.com/user-attachments/assets/d1c7fb75-1b53-40ba-9afa-6744f98ba586" /></p>


#### Step 3 – Boundary Definition
- The cleaning area is defined using visual markers.
- Three black lines indicate the left, right, and bottom boundaries.
- A red dot marks the bottom-right corner.
- A white dot marks the bottom-left corner.
- Line tracking sensors use these markers to guide device movement.

<p align="center"><img width="713" height="557" alt="image" src="https://github.com/user-attachments/assets/b2282f03-a881-47de-b1fc-f0b154df60c3" /></p>

#### Step 4 – Device Mounting
- The device is mounted onto the magnetic board.
- Four neodymium magnets provide secure attachment.
- The wheels and cleaning pad maintain equal contact with the board surface.

<p align="center"><img width="896" height="636" alt="image" src="https://github.com/user-attachments/assets/36e9da6d-7536-4fef-964a-29b15be7fcbd" /></p>


#### Step 5 – Cleaning Initiation
- The user starts the cleaning cycle through the application.
- The peristaltic pump wets the microfiber cleaning pad.
- Once the pad is sufficiently wet, the device begins moving horizontally along the X-axis.
- The line tracker detects the right boundary and signals the controller to stop horizontal motion.

<p align="center"><img width="901" height="633" alt="image" src="https://github.com/user-attachments/assets/f2d3dd0e-94b0-429e-80c7-66ce62671e0c" /></p>


#### Step 6 – Vertical Movement
- The stepper motor is activated.
- The device moves downward along the Y-axis.
- The movement distance is calculated using the board height entered by the user.

<p align="center"><img width="956" height="522" alt="image" src="https://github.com/user-attachments/assets/0a0db218-b78d-4017-bf9b-a742fe6fd092" /></p>


#### Step 7 – Zigzag Cleaning Pattern
- After moving vertically, the servo motor reverses direction.
- The device moves horizontally in the opposite direction.
- This process repeats, creating a zigzag cleaning pattern across the board.
- Cleaning continues until the device reaches the red marker.

<p align="center"><img width="930" height="500" alt="image" src="https://github.com/user-attachments/assets/c0ab439c-1d0a-4a5d-a04a-b82f3335dadf" /></p>

#### Step 8 – End-of-Cleaning Detection
- An IR sensor detects the red marker at the bottom-right corner.
- The device recognizes that the cleaning cycle is nearly complete.
- The servo motor moves the device toward the white marker.

<p align="center"><img width="986" height="502" alt="image" src="https://github.com/user-attachments/assets/da5be542-f09b-45a3-8bbb-2ad094cdc92c" /></p>


#### Step 9 – Completion Detection
- The device continues moving left until the white marker is detected.
- Detection of the white marker indicates that the cleaning process has been completed.

<p align="center"><img width="1012" height="523" alt="image" src="https://github.com/user-attachments/assets/e2f8f535-8cc4-4b86-ad1e-e227d86c09b1" /></p>


#### Step 10 – Return to Standby
- The device returns to its default position.
- The system enters standby mode and waits for the next cleaning command.

<p align="center"><img width="756" height="487" alt="image" src="https://github.com/user-attachments/assets/629e8f79-fc46-473f-8517-1e765d4e34b9" /></p>

###  Component List & Cost Estimation

| Component | Qty | Description | Unit Cost (€) | Total Cost (€) |
|------------|-----|-------------|---------------|----------------|
| LCD Display | 1 | Device status display | 5.99 | 5.99 |
| ESP32 Microcontroller | 1 | Main control unit | 11.98 | 11.98 |
| LM2596 Buck Converter | 2 | Voltage regulation (12V → 5V/3.3V) | 2.19 | 4.38 |
| NEMA 17 Stepper Motor | 2 | Vertical (Y-axis) movement | 14.99 | 29.98 |
| LED Push Button | 1 | Device activation and status indication | 8.99 | 8.99 |
| MG996R Servo Motor (360°) | 2 | Horizontal (X-axis) movement | 8.09 | 16.18 |
| TCRT5000 Line Follower Sensor | 3 | Boundary detection | 1.99 | 5.97 |
| 12V 4000mAh Li-Ion Battery | 1 | Portable power supply | 17.56 | 17.56 |
| Peristaltic Pump | 1 | Cleaning fluid delivery | 19.55 | 19.55 |
| Brushless Cooling Fan (30×30 mm) | 2 | Thermal management | 5.35 | 10.69 |
| TMP36 Temperature Sensor | 2 | Temperature monitoring | 2.58 | 5.16 |
| Neodymium Magnets | 4 | Board attachment | 1.67 | 6.68 |
| 3D Printed Wheels | 4 | Device movement | - | 0.64* |
| Water Tube | 1 | Fluid transport | 3.44 | 3.44 |
| Microfiber Cleaning Pad | 1 | Board cleaning | 3.00 | 3.00 |
| 3D Printed Housing | 1 | Main device enclosure | - | 7.50* |
| | | | **Total Estimated Cost** | **163.70 €** |

Estimated material cost only. Manufacturing and labor costs are not included. 

## Technical Validation

| Validation Area | Description | Result |
|----------------|-------------|---------|
| Magnetic Holding Force | The device weighs approximately **1.5 kg** and is supported by four neodymium magnets. After accounting for gravity and a 2 mm board-to-metal gap, the effective holding force was calculated to be **105.46 N**. | Magnetic attachment is sufficient to securely hold the device during operation. |
| Battery Runtime | A **12V 4000mAh Li-Ion battery** provides a total energy capacity of **48 Wh**. Assuming a realistic 30% duty cycle for motors, pump, and cooling fans, the estimated runtime is **99 minutes**. | Exceeds the project requirement of **90 minutes** runtime. |
| Servo Motor Force (X-Axis) | The servo motors generate approximately **61.4 N** of linear force. Estimated magnetic friction was calculated as **70.63 N** and distributed across multiple drive points. | Sufficient force available for horizontal movement and board traversal. |
| Stepper Motor Force (Y-Axis) | The stepper motors generate approximately **18 N** of linear force. Gravity assists downward movement and opposes upward movement during return-to-home operation. | Sufficient force available for both downward and upward movement. |
| Cleaning System Feasibility | The peristaltic pump distributes cleaning fluid through tubing positioned above the microfiber cloth, ensuring even wetting without dripping. | Supports consistent cleaning performance across the board surface. |
| Thermal Management | Temperature sensors continuously monitor component temperatures, while cooling fans activate only when predefined temperature thresholds are exceeded. | Prevents overheating of the battery, motors, and ESP32 controller. |

### Summary

The technical calculations confirmed that the proposed concept satisfies the key engineering requirements. The magnetic attachment system provides sufficient holding force, the battery meets the required operating time, and the selected motors are capable of overcoming the expected movement resistance during cleaning. These results demonstrate the technical feasibility of the concept before prototype development.

### Technical Drawings 
<img width="836" height="648" alt="image" src="https://github.com/user-attachments/assets/8dec938b-2fcf-4cdb-9582-7421cc5a5616" />

<img width="881" height="547" alt="image" src="https://github.com/user-attachments/assets/8bf66e7e-90d5-45b8-9274-7b830ac71d97" />

<img width="900" height="572" alt="image" src="https://github.com/user-attachments/assets/2d3813a6-ebcd-4d46-96a6-21832f5ba315" />
<img width="912" height="673" alt="image" src="https://github.com/user-attachments/assets/a11ebb52-d070-43fa-a88f-e8d0a84d16df" />
<img width="915" height="697" alt="image" src="https://github.com/user-attachments/assets/9ff74228-fca1-4a87-a553-45c215ab0261" />

### Requirement Compliance
<p align="center"><img width="503" height="737" alt="image" src="https://github.com/user-attachments/assets/b07a8d57-1921-427f-89d5-f9adffa08387" /></p>
<p align="center"><img width="523" height="768" alt="image" src="https://github.com/user-attachments/assets/a66219e3-307c-4af6-b687-495604ba7c32" /></p>
<p align="center"><img width="527" height="147" alt="image" src="https://github.com/user-attachments/assets/cb28032f-1951-408a-9433-7f7e9204a80c" /></p>

## Concept Evaluation & Optimized Variant

After all individual concept variants were developed, the team evaluated them from both a technical and an economic perspective. The purpose of this evaluation was to identify the most suitable concept for further development and optimization.

The evaluation considered factors such as technical feasibility, fulfilment of requirements, usability, manufacturing complexity, cost, and overall product potential.

My concept variant achieved:

| Evaluation Perspective | Score |
|------------------------|-------|
| Technical Evaluation | 82% |
| Economic Evaluation | 79% |

Based on this combined evaluation, my variant was selected as the winning concept and was further developed into the optimized final design.

### Technical and Economic Evaluation Matrix
<img width="928" height="737" alt="image" src="https://github.com/user-attachments/assets/4cd18643-d853-4d5f-b00d-39670061962f" />
<img width="720" height="533" alt="image" src="https://github.com/user-attachments/assets/7ef8ef0f-f499-4b42-ba0a-566423ba5626" />

## Optimized Variant

After the concept evaluation, the selected variant was further refined to improve performance, manufacturability, and overall reliability.

| Optimization Area | Improvement |
|------------------|-------------|
| Wheel Friction Management | Replaced microfiber-coated wheels with rubber-coated wheels to improve traction and maintain consistent movement. |
| Stability & Center of Gravity | Removed the central screwing mechanism and relocated the mounting point to improve balance and overall stability. |
| Air Ventilation Design | Redesigned ventilation openings to improve airflow while reducing dust ingress. |
| Motor Integration | Refined the wheel and motor geometry through CAD revisions to improve alignment and movement accuracy. |
| Structural Design | Split the housing into upper and lower sections to simplify manufacturing and assembly. |
| 3D Printing Optimization | Redesigned components specifically for additive manufacturing and printability verification. |
| Cost & Production Planning | Developed a complete Bill of Materials (BOM) and performed a detailed cost analysis to support future production planning. |

### Optimized Concept
<img width="721" height="252" alt="image" src="https://github.com/user-attachments/assets/b66c6d9e-4287-426f-95bb-3d5b152fc386" />
<img width="840" height="435" alt="image" src="https://github.com/user-attachments/assets/3991cab6-e6d1-498b-8655-113dbe04e58c" />
<img width="808" height="197" alt="image" src="https://github.com/user-attachments/assets/a2c6cc65-238b-4fcd-aa8a-712803a4dbea" />

**Note:** The optimized concept is on the right. 

### Technical Drawings
<img width="812" height="596" alt="image" src="https://github.com/user-attachments/assets/a50e7841-6d93-4e3c-b4d4-dd6bbb9c85f1" />
<img width="942" height="640" alt="image" src="https://github.com/user-attachments/assets/855ef134-dd38-456e-af55-699eb35d1177" />
<img width="940" height="708" alt="image" src="https://github.com/user-attachments/assets/ad3b9227-f2b7-4a23-a433-636853bd9be3" />

### Additional Technical Validation

To further validate the optimized concept, several engineering analyses were conducted covering mechanical performance, power requirements, component compatibility, and system stability.

| Validation Area | Key Calculation | Result |
|----------------|----------------|---------|
| Magnetic Holding Force | Device Weight = **1.51 kg (14.79 N)**, Total Magnetic Force = **117.72 N**, Net Holding Force = **102.93 N** | Magnetic force is more than **6×** the device weight, ensuring secure attachment. |
| Wheel Traction & Motion | Friction Coefficient (Rubber) = **1.2**, Available Traction Force ≈ **3.84 kg** | Sufficient traction for movement on vertical board surfaces. |
| Cleaning Efficiency | Cleaning Pad Area ≈ **329 cm²**, Estimated Cleaning Pressure ≈ **65.8 N** | Adequate pressure for marker and chalk residue removal. |
| Servo Motor Torque (X-Axis) | Motor Force = **432.2 N**, Required Force = **62.38 N** | Available force exceeds requirement by approximately **7×**. |
| Stepper Motor Torque (Y-Axis) | Motor Force = **180 N**, Required Upward Force = **70.13 N** | Stepper motor provides sufficient force for vertical movement. |
| Magnetic Force Verification | Required magnetic force (with safety factor) = **84.08 N**, Available magnetic force = **117.72 N** | Available magnetic force exceeds the required force, ensuring secure attachment and stable operation. |
| Center of Gravity Analysis | CoG = **(117.5 mm, 70 mm)**, Magnetic Stabilizing Torque = **11.03 Nm** | Center of gravity remains within magnet footprint, ensuring stability. |
| Component Compatibility | ESP32 GPIO Used = **15 Pins**, ESP32 Available = **34 Pins** | All components successfully integrated within controller limitations. |
| Battery Runtime Analysis | Battery Capacity = **48 Wh**, Average Power Draw = **24.5 W**, Runtime = **1.9 Hours** | Exceeds the required **90-minute** operating time. |

**Note:** The runtime increased after optimization due to revised component selection and updated power consumption calculations.

The calculations confirmed that the optimized design satisfies the key engineering requirements for magnetic attachment, motor performance, stability, component compatibility, and battery runtime.

## Failure Mode and Effects Analysis (FMEA)

An FMEA was conducted to identify potential failure modes in the optimized design and evaluate their impact on device performance, safety, and reliability. The analysis helped assess risks related to movement, attachment, cleaning performance, power supply, and user interaction.

The main purpose of the FMEA was to identify possible technical risks early and define preventive or corrective actions before prototype testing.

### FMEA Overview

<img width="1362" height="817" alt="image" src="https://github.com/user-attachments/assets/938d38a5-8cb1-4367-a226-419e55a21e33" />
<img width="1247" height="657" alt="image" src="https://github.com/user-attachments/assets/ab79f205-45fe-4cd7-9b6e-0faa1e9715d9" />
<img width="1253" height="251" alt="image" src="https://github.com/user-attachments/assets/86bc120e-b064-42a0-99b5-18a72edb6a41" />
<img width="1287" height="751" alt="image" src="https://github.com/user-attachments/assets/52df5a82-ff7c-451e-925e-2590f12acee5" />
<img width="1282" height="180" alt="image" src="https://github.com/user-attachments/assets/39c5675b-ed0f-43b6-a58b-f0f3f7e3aca7" />
<img width="1198" height="372" alt="image" src="https://github.com/user-attachments/assets/45351f1d-e41b-49f1-ba0d-34edff6150f0" />
<img width="1202" height="537" alt="image" src="https://github.com/user-attachments/assets/01b57e21-a2c9-4583-a7d1-ff26a6f06e4d" />
<img width="1292" height="232" alt="image" src="https://github.com/user-attachments/assets/b30562fc-ffe1-45e5-8bdf-662b809b534a" />
  
## Prototype Development
### 3D Printing 
From the 3D design, an STL file was generated which was used to 3D print with NX2 material, resulting in a high-strength prototype suitable for assembly. 
<img width="930" height="372" alt="image" src="https://github.com/user-attachments/assets/766fd8b4-39f8-4fa3-ad0c-c15f8d58fafc" />
**Note:** The Left side is the 3D model and the Right side is the 3D printed model. 

### Wiring Diagram 
#### Wiring of the Stepper Motor Driver
<p align="center"><img width="496" height="358" alt="image" src="https://github.com/user-attachments/assets/08c0b847-58b9-4627-ba2a-ae190cc581d4" /><p>

- The VMOT and GND pins of the stepper motor driver are connected to the + & - terminal of the 
battery.  
- 2B&2A is connected to the 2nd coil of the Stepper motor  
- 1A & 1B is connected to the 1st coil of the Stepper motor 
- VDD is connected to the 5V power supply from the ESP32 Break board (This is achieved 
when the jumper clip of the break board is set to the value of 5V(Yellow clip)) 
- GND is connected to the GND of the ESP32 Break Board  
- STEP is connected to one of the GPIO of the ESP32 Break Board  
- DIR is connected to one of the GPIO of the ESP32 Break Board  
- RST and SLP are connected together, SLP pin put the driver into a low power mode when 
pulled low (Disabled) and the RST pin resets the internal logic of the driver when pulled low. 
If either of the pins are left floating or pulled low, the driver won’t operate. 

#### Wiring diagram of the prototype
<p align="center"><img width="636" height="378" alt="image" src="https://github.com/user-attachments/assets/cad15fa7-dc53-4755-8310-e07354dae28b" /><p>

- An ESP32 Break Board is used as the main controller for the prototype.
- Two NEMA 17 stepper motors are controlled through two A4988 stepper motor drivers.
- The first stepper motor driver uses:
  - STEP → GPIO 22
  - DIR → GPIO 23
- The second stepper motor driver uses:
  - STEP → GPIO 19
  - DIR → GPIO 21
- The SLP (Sleep) and RST (Reset) pins of each A4988 driver are connected together and pulled high to VCC to keep the drivers continuously enabled.
- Both motor drivers are powered by a 12V battery supply connected through the breadboard power rails.
- A 220 µF capacitor is included to reduce voltage fluctuations and electrical noise.
- Each stepper motor is connected to the output terminals of its respective motor driver.
- Two TCRT5000 line follower sensors are connected to:
  - GPIO 34
  - GPIO 35
- The line follower sensors are used for boundary detection and navigation.
- The ESP32 Break Board includes an integrated buck converter that steps down the 12V supply to the 5V and 3.3V levels required by the controller.
- All grounds (GND) from the ESP32, motor drivers, sensors, and power supply are connected together to provide a common reference and ensure stable operation.

### C++ Code 
The prototype was programmed using C++ on the ESP32 platform.
```cpp
#include <WiFi.h> // This imports the library function "WiFi" (This is case sensitive)

// Stepper Motor Pins 
const int dirPin1 = 23;
const int stepPin1 = 22;
const int dirPin2 = 21;
const int stepPin2 = 19;

// TCRT5000 Sensor Pins
const int sensor1Pin = 34;
const int sensor2Pin = 35;

// States (We are declaring the boolean variables and giving them an initial value as false)
bool isRunning = false;
bool isReversed = false;
bool boundaryHit = false;

// WiFi Access Point Config (We are creating a WiFi module with the name "ESP32_Control" and assigning password as "12345678")
const char* ssid = "ESP32_Control";
const char* password = "12345678";
WiFiServer server(80); // This function starts a web server on port 80, which is the standard port for HTTP
// This port is easier and it's the default HTTP Web server, but to use port 443 (which is for HTTPS and more secure),
// we need to add more libraries

void setup() {
  Serial.begin(115200); // To communicate with the serial monitor using the baud rate 115200
  // Baud rate is the speed at which the communication happens between the computer and the ESP32
  // Baud rate 115200 is used for faster bits/second transmission

  // Config of the GPIO pins to make the ESP32 understand that certain PINS are for output and certain for input
  pinMode(dirPin1, OUTPUT);
  pinMode(stepPin1, OUTPUT);
  pinMode(dirPin2, OUTPUT);
  pinMode(stepPin2, OUTPUT);
  pinMode(sensor1Pin, INPUT);
  pinMode(sensor2Pin, INPUT);

  setMotorDirection();

  WiFi.softAP(ssid, password);
  Serial.print("WiFi AP started. IP: ");
  Serial.println(WiFi.softAPIP());
  server.begin();
}

void loop() { // Loop to make the function run continuously
  WiFiClient client = server.available(); // Waits for the browser to connect to the ESP32 
  if (client) { // This checks if the client is connected 
    String request = client.readStringUntil('\r'); // Reads the full HTTP GET request from the browser
    // String will look like GET/start or GET/stop or GET/reverse 
    client.flush(); // Clears any remaining characters in the input buffer 

    if (request.indexOf("/start") != -1) { // This function checks if the user wants to start the device 
      isRunning = true; // To start the motor to move forward 
      isReversed = false;
      boundaryHit = false;
      setMotorDirection();
      Serial.println("Start command received."); // Output shown on the Arduino IDE 
    }
    else if (request.indexOf("/stop") != -1) {
      isRunning = false;
      Serial.println("Stop command received."); // Output shown on the Arduino IDE
    }
    else if (request.indexOf("/reverse") != -1) { // This function checks if the user wants to start the device but in the opposite direction 
      isReversed = true;
      isRunning = true;        // Allow user to resume manually in reverse
      boundaryHit = false;     // Clear boundary only after explicit reverse
      setMotorDirection(); // This flips the stepper motor direction 
      Serial.println("Reverse command received."); // Output shown on the Arduino IDE
    }

    client.println("HTTP/1.1 200 OK"); // Checks if the response is OK
    client.println("Content-type:text/html\r\n"); // Specifying the content type is HTML
    client.println("<html><body><h2>Stepper Motor Control</h2>"); // Webpage is being created with the TITLE Stepper Motor Control (Body open)
    client.println("<p><a href=\"/start\"><button>Start (Forward)</button></a></p>"); // Linking the start function to the button Start (Forward)
    client.println("<p><a href=\"/reverse\"><button>Reverse</button></a></p>"); // Linking the reverse function to the button Reverse
    client.println("<p><a href=\"/stop\"><button>Stop</button></a></p>"); // Linking the stop function to the button Stop
    client.println("</body></html>"); // We close the body
    client.stop();
  }

  if (isRunning && !boundaryHit) {
    bool sensor1Triggered = digitalRead(sensor1Pin) == LOW; // This is if the IR sensor detects a boundary 
    bool sensor2Triggered = digitalRead(sensor2Pin) == LOW;

    if (sensor1Triggered || sensor2Triggered) {
      boundaryHit = true;
      isRunning = false;
      Serial.println("Boundary detected! Motors stopped."); // Output on the Arduino IDE
      return;
    }

    // Step both motors
    digitalWrite(stepPin1, HIGH);
    digitalWrite(stepPin2, HIGH);
    delayMicroseconds(3000);
    digitalWrite(stepPin1, LOW); // Because the motors move in the opposite direction 
    digitalWrite(stepPin2, LOW);
    delayMicroseconds(3000); // Speed of rotation, in microseconds 
  }
}

void setMotorDirection() {
  digitalWrite(dirPin1, isReversed ? LOW : HIGH);
  digitalWrite(dirPin2, isReversed ? HIGH : LOW);
}
```
### Full Assembly 
#### Full Assembly Prototype and Testing Results

The prototype was assembled by integrating all mechanical and electronic components into the main housing. Due to project time constraints, the prototype focused on validating the core concept, specifically magnetic attachment, motor-driven movement, boundary detection, and cleaning functionality.

The system used a 12V battery, ESP32 microcontroller, NEMA 17 stepper motor, and stepper motor driver to drive a rubber-coated wheel through a shaft coupling. A metal mounting bracket ensured proper motor alignment and efficient torque transmission. Boundary detection was achieved using line follower sensors, while Wi-Fi communication allowed the user to remotely start and stop the device through the ESP32.

#### Testing Results

- Successfully attached to the board using the designed magnetic mounting system.
- Successfully moved along the board surface using the motor-driven wheel mechanism.
- Successfully detected board boundaries and stopped when required.
- Successfully received user commands through ESP32 Wi-Fi communication.
- Successfully removed chalk residue from blackboards.
- Successfully removed marker residue from whiteboards.

Overall, the prototype demonstrated the feasibility of the proposed concept and validated the key design assumptions developed during the product development process.
<p align="center"><img width="510" height="382" alt="image" src="https://github.com/user-attachments/assets/8b5eccc3-fc25-4c39-a760-53750e601b5a" /><p>

<p align="center"><img width="490" height="562" alt="image" src="https://github.com/user-attachments/assets/4fb04f71-3eb1-4905-9073-ef70966b1602" /><p>

## Lessons Learned & Future Improvements

Throughout the prototyping phase, several technical challenges were encountered related to electronics integration, programming, torque transmission, and mechanical assembly. Resolving these issues provided valuable practical experience and highlighted areas for future improvement.

### Key Lessons Learned

| Challenge | Solution | Lesson Learned |
|------------|----------|----------------|
| Power supply distribution between the ESP32, motor drivers, and battery | Improved wiring layout and soldered critical connections | Better understanding of power distribution, ESP32 integration, and motor driver setup |
| Software bugs and control logic issues | Reviewed and refined the C++ control logic | Improved understanding of ESP32 programming and Arduino IDE development |
| Torque transmission between the motor and wheel | Introduced a suitable shaft coupling | Learned the importance of proper mechanical power transmission |
| Wheel alignment issues | Adjusted mounting positions and improved assembly tolerances | Gained experience in mechanical alignment and assembly techniques |

### Areas for Future Improvement

#### Power Supply & Circuit Integration
- Improve circuit design for more efficient power distribution.
- Enhance soldering and electrical integration practices.
- Improve reliability of ESP32 and motor driver connections.

#### Software Development
- Further develop C++ programming skills.
- Improve software structure and code maintainability.
- Expand ESP32 functionality and user interface features.

#### Mechanical Design
- Optimize the motor-to-wheel coupling mechanism.
- Improve torque transmission efficiency.
- Refine component sizing and mechanical tolerances.

#### Assembly & Alignment
- Improve mounting and alignment methods.
- Reduce assembly complexity.
- Increase overall mechanical robustness and reliability.

### Prototype Demonstration

The demonstration videos below show the prototype operating on both blackboards and whiteboards. These tests confirmed that the device could securely attach to the board, move along the surface, detect boundaries, and remove writing residue as intended.

### Demonstration Videos

🎥 Blackboard Cleaning Test

https://github.com/user-attachments/assets/f0ea98c9-4e8e-41f8-adbd-614c7ab1a2e4

🎥 Whiteboard Cleaning Test

https://github.com/user-attachments/assets/0c2fc63c-7af1-4f56-a211-4ccc73d67504

## Conclusion

This project followed a complete product development cycle, beginning with requirements engineering and concept generation and progressing through concept evaluation, optimization, technical validation, risk assessment, and prototype development.

The final prototype successfully demonstrated the feasibility of the proposed automated board-cleaning device and validated the core design principles through practical testing.

The project provided valuable experience in product development, CAD design, embedded systems, electronics integration, engineering calculations, prototyping, and teamwork.

---
## License

Copyright (c) 2026 Rithik Paul Vaimel. All Rights Reserved.

This project is provided for viewing purposes only. No permission is granted to copy, modify, or redistribute any part of this repository without explicit written consent from the author.

![License](https://img.shields.io/badge/License-All%20Rights%20Reserved-red)

---
