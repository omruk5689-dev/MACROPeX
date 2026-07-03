| | |
|----------------|-------------------------------------------------------------|
| **title** | **MACROPeX** |
| **author** | **Omer** |
| **description** | A fully open-source 9-key macro pad powered by the Raspberry Pi RP2040 featuring a custom PCB, rotary encoder, RGB lighting, VIA firmware support, and a custom 3D-printed enclosure. |
| **created_at** | **2026-07-03** |


# Total Time Spent *45 Hours*


> **Software Used:**  
> The entire schematic and PCB were designed using **EasyEDA Pro**, which is available as both an online and desktop PCB design software. Component datasheets, the Raspberry Pi RP2040 datasheet, and manufacturer documentation were used throughout the project to ensure a reliable design.

---

# 📅 Day 1 (6 Hours)
<img width="1126" height="561" alt="Screenshot 2026-07-03 120250" src="https://github.com/user-attachments/assets/037dc58a-f9b3-4f38-966d-befc375cc307" />


## Project Planning & RP2040 Circuit

The project started by creating a new project in EasyEDA Pro. After setting up the workspace, the Raspberry Pi RP2040 microcontroller was selected as the main controller for the macro pad.

Using the RP2040 datasheet as a reference, the complete supporting circuitry was designed, including all required components for proper operation.
<img width="1354" height="622" alt="Screenshot 2026-07-03 120359" src="https://github.com/user-attachments/assets/1f1f95f0-3f35-4ce8-a0e1-ee429c93c872" />

### Work Completed

- Created the MACROPeX project.
- Selected Raspberry Pi RP2040.
- Arranged the schematic for cleaner connections.
- Added USB Type-C connector.
- Added all required capacitors and resistors.
- Added BOOTSEL button.
- Added RESET button.
- Added Debug Header.
- Added required GPIO expansion pins.
- Added User LED.
- Added Power LED.
- Named important signals for easier debugging.
- Selected switch mounting components.
- Modified footprints according to manufacturer specifications.
- Imported official 3D models for hardware components.

---

# 📅 Day 2 (6 Hours)

## Keyboard Matrix Design
<img width="1295" height="439" alt="Screenshot 2026-07-03 120730" src="https://github.com/user-attachments/assets/070d4bbd-8820-460d-91bf-88c234fcce51" />
The second day focused on designing the keyboard matrix and preparing all mechanical switch components.

<img width="1330" height="538" alt="Screenshot 2026-07-03 120941" src="https://github.com/user-attachments/assets/f3d84e4f-1132-46e8-9509-87a3e36fc1a0" />

Each switch was selected carefully and edited according to its datasheet to ensure correct footprint dimensions.
<img width="833" height="336" alt="Screenshot 2026-07-03 121211" src="https://github.com/user-attachments/assets/cf6f8de7-b3f1-4051-ba97-a2e9846895a8" />
<img width="862" height="397" alt="Screenshot 2026-07-03 121233" src="https://github.com/user-attachments/assets/5acff94f-c41c-4206-99d2-49dcf6d8003b" />

### Work Completed

- Selected mechanical switches.
- Modified switch device properties.
- Updated footprints according to datasheets.
- Imported official 3D switch models.
- Added all 9 keyboard switches.
- Connected switches using a keyboard matrix.
- Connected switches through diodes.
- Connected keyboard matrix to RP2040 GPIO pins.
- Selected rotary encoder.
- Planned firmware implementation for encoder.

---

# 📅 Day 3 (6 Hours)
<img width="1407" height="530" alt="Screenshot 2026-07-03 120917" src="https://github.com/user-attachments/assets/467f9b87-e02a-4ea6-92ab-0db77c42efba" />
## Encoder & Schematic Completion
<img width="1295" height="439" alt="Screenshot 2026-07-03 120730" src="https://github.com/user-attachments/assets/070d4bbd-8820-460d-91bf-88c234fcce51" />

The encoder section was completed and connected to the RP2040.

Additional supporting circuitry was verified to complete the schematic before starting PCB design.

### Work Completed

- Added rotary encoder.
- Edited encoder footprint.
- Verified dimensions using manufacturer datasheets.
- Connected encoder to RP2040.
- Added required resistors.
- Added required capacitors.
- Connected power and ground.
- Added optional encoder filtering.
- Completed keyboard schematic.
- Verified Flash circuitry.
- Verified 5V to 3.3V power section.
- Verified RESET circuit.
- Verified Power LED circuit.
- Completed the full schematic.

---

# 📅 Day 4 (6 Hours)

## RGB LEDs & Mechanical Preparation
<img width="876" height="394" alt="Screenshot 2026-07-03 121526" src="https://github.com/user-attachments/assets/f27e6a59-745e-48c7-9457-fb1bb9720680" />

The fourth day focused on RGB lighting and preparing the PCB for the enclosure.
<img width="638" height="347" alt="Screenshot 2026-07-03 121609" src="https://github.com/user-attachments/assets/01b64f29-2224-436f-b287-252272e0271b" />

### Work Completed
<img width="582" height="277" alt="Screenshot 2026-07-03 121644" src="https://github.com/user-attachments/assets/ce6d8e22-2222-435d-8661-141c35934510" />

- Selected RGB LEDs for every key.
- Modified LED device properties.
- Connected RGB LEDs.
- Connected LEDs to RP2040.
- Added power and ground connections.
- Verified RGB wiring using reference designs.
- Added PCB mounting holes.
- Calculated mechanical spacing.
- Imported additional 3D models.
- Updated footprints according to mechanical dimensions.

By the end of Day 4, the complete schematic was finished and the PCB design was ready to begin.

---

# 📅 Day 5 (8 Hours)

## PCB Layout & Component Placement
<img width="854" height="382" alt="Screenshot 2026-07-03 135938" src="https://github.com/user-attachments/assets/a48b4b92-d525-466b-a581-8258e0b26a62" />

Day 5 was dedicated to designing the PCB layout.
<img width="832" height="373" alt="Screenshot 2026-07-03 140001" src="https://github.com/user-attachments/assets/bfeea186-883f-4962-b398-e8fdb55119a7" />

The first task was creating mounting holes for the 54 mm aluminium top plate before placing every component on the PCB.

### Work Completed
<img width="862" height="384" alt="Screenshot 2026-07-03 140107" src="https://github.com/user-attachments/assets/d4fff750-e348-4cf4-9b3f-5b662c204ea3" />

- Added mounting holes for the aluminium plate.
- Added PCB mounting holes.
- Drew the PCB outline.
- Positioned the USB Type-C connector.
- Positioned the rotary encoder.
- Positioned all 9 keyboard switches.
- Positioned RGB LEDs.
- Placed RP2040.
- Placed passive components.
- Arranged components on both top and bottom layers.
- Optimized component spacing.
- Started routing the PCB.
- Routed power traces.
- Routed USB signals.
- Routed keyboard matrix traces.
- Routed encoder signals.
- Connected supporting circuitry.
<img width="823" height="366" alt="Screenshot 2026-07-03 140135" src="https://github.com/user-attachments/assets/493ec299-e0d3-48e5-9396-a46badf4eabd" />

PCB routing required several adjustments to maintain proper spacing and clean electrical connections.

---

# 📅 Day 6 (13 Hours)
<img width="844" height="353" alt="Screenshot 2026-07-03 140409" src="https://github.com/user-attachments/assets/84d581bf-3d92-4e59-b5a3-2cb2c568af7c" />
<img width="314" height="299" alt="Screenshot 2026-07-03 140517" src="https://github.com/user-attachments/assets/b88358ec-46b2-435b-b9a0-54e985764fc5" />
<img width="882" height="370" alt="Screenshot 2026-07-03 140426" src="https://github.com/user-attachments/assets/f6c2a205-d32f-4877-90d0-8d693465cea6" />

## PCB Completion & 3D Case Design

The final day focused on completing the PCB routing, making final improvements, and designing the enclosure.

Several routing changes were made to improve signal quality and simplify difficult PCB traces.
<img width="778" height="410" alt="Screenshot 2026-07-03 140556" src="https://github.com/user-attachments/assets/236b2070-06ac-4c85-ace3-2df7abf5f991" />

### Work Completed

### PCB

- Completed all remaining routing.
- Connected every remaining component.
- Improved PCB routing.
- Added finishing touches.
- Verified all electrical connections.
- Performed final PCB inspection.

### 3D Enclosure
<img width="853" height="420" alt="Screenshot 2026-07-03 140656" src="https://github.com/user-attachments/assets/e48e246f-64b5-4d2e-b2db-8854d3d687b9" />
<img width="694" height="294" alt="Screenshot 2026-07-03 140625" src="https://github.com/user-attachments/assets/3764fe86-4634-49e6-aba0-6e369a277600" />

After completing the PCB, a custom enclosure was designed.

The enclosure includes:

- 9 switch openings.
- Rotary encoder opening.
- USB Type-C cut-out.
- Power LED openings.
- PCB mounting posts.
- Mounting screw holes.
- Internal support structure.

The enclosure was designed to perfectly match the PCB dimensions while maintaining a clean appearance.

---

# ✅ Final Result

After approximately **45 hours** of development across **6 days**, the MACROPeX project was successfully completed.

The project includes:

- Custom RP2040 PCB
- Mechanical Keyboard Matrix
- Rotary Encoder
- RGB Lighting
- VIA Support
- Custom Firmware
- Custom 3D Printable Case
- Complete Documentation
- Open Source Design Files

---

# 📷 Project Gallery



## Schematic
<img width="3332" height="2362" alt="SCH_MACROPeX_2-OTHER_2026-07-03" src="https://github.com/user-attachments/assets/4a14759a-b4f1-4186-b86f-73be502b8fab" />
<img width="3332" height="2362" alt="SCH_MACROPeX_1-MCU_2026-07-03" src="https://github.com/user-attachments/assets/d854aec1-da8f-4741-88a5-16685099bd41" />


## PCB Layout

<img width="2160" height="4090" alt="PCB_pcb_2026-07-03" src="https://github.com/user-attachments/assets/552c5e92-a128-445b-85c2-ec0f71a6fa70" />


## 3D PCB View

<img width="578" height="639" alt="MACROPeX Front IMG" src="https://github.com/user-attachments/assets/60174786-6101-43e0-b25f-0851b3c14d18" />
<img width="442" height="629" alt="MACROPeX Back IMG" src="https://github.com/user-attachments/assets/95eb74b5-caaf-488e-bcd7-63f3f08c30c2" />


## Final MACROPeX

<img width="2160" height="2775" alt="3D_pcb_2026-07-03" src="https://github.com/user-attachments/assets/42e7b462-a26c-4343-886d-3e146c76e593" />


