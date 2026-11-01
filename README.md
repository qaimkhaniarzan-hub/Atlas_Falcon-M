
# Atlas Cargo Airplane

Atlas is a custom scratch-built radio-controlled (RC) cargo airplane designed using foamboard, a twin-motor setup, and modular electronic systems. It is meant to House my custom aerial vehicle called Falcon X
> Both are currently under developement
> This repository contains the complete Bill of Materials (BOM), 3D design models, 2D printable templates, electrical layouts, and step-by-step build documentation.

<img width="1365" height="768" alt="gaga" src="https://github.com/user-attachments/assets/c4483255-7ae2-4acf-ad6e-42f3077bd0d8" />

> **Project Goal:** Build a reliable, high-payload foamboard cargo plane under a strict budget ceiling of $600 USD (SAR 2,250).

---

## About The Project

Since I was young, I've always loved airplanes! Over the last couple of years, I really wanted to build my own RC plane, but I lacked the motivation and funding to bring it to life. Getting the opportunity to build Atlas makes this project an incredible journey, and it's going to be very fun to construct, test, and fly.

---

## Progress So Far

COMPLETE **Project Scoping & Design:** Defined payload goals, twin-motor configuration, and channel requirements.  
COMPLETE **Bill of Materials (BOM):** Selected all 20 hardware items, tools, and electronics within the $600 USD budget ceiling.  
COMPLETE **Repository & CAD Modeling:** Created GitHub project structure and completed full 3D airframe blockout in Blender.  
BLEHH NOT DONE YET **Verification & Funding:** Finalizing verification approval to secure project grant funds.  
BLEHH NOT DONE YET **Templates & Printing:** Generating 1:1 scale printable 2D foamboard templates.  
BLEHH NOT DONE YET **Airframe Build:** Cutting foamboard and assembling the fuselage, wing spar, and control surfaces.  
BLEHH NOT DONE YET **Electronics & Maiden Flight:** Installing power system, servos, camera, and completing first test flight.  

---

## Technical Specifications

| Feature | Specification |
| :--- | :--- |
| **Airframe Material** | 5mm Foamboard & Bamboo Reinforcements |
| **Control Channels** | 10 Channels (FlySky i6X + iA10B Receiver) |
| **Power System** | Twin Brushless Motors + ESCs |
| **Flight Battery** | 3S LiPo System |
| **Onboard Camera** | SQ11 1080p HD Action Cam (MicroSD Recording) |
| **Special Features** | Retractable Landing Gear & Payload Parachute Drop |

---

## Bill of Materials (BOM)

The full component list and budget breakdown are tracked below.

| Item Name | Quantity | Price (SAR) | Price (USD) |
| :--- | :--- | :--- | :--- |
| Foam Board | 4 Sheets | 360.00 | $37.20 |
| Skewer | 100 Pc | 4.50 | $1.22 |
| Steel Pushrods | 10 | 98.00 | $26.46 |
| Control Horns / Clevises | 20 Pc | 57.00 | $15.39 |
| Motor Pack with ESCs | 2 Sets | 126.00 | $34.02 |
| Controller / Receiver Pack | 1 (i6X + iA10B) | 361.00 | $97.47 |
| Servos | 10 Pack | 75.00 | $20.25 |
| Battery | 2 Pcs | 269.00 | $72.63 |
| Battery Charger | 1 | 112.00 | $30.24 |
| Landing Gear Base | 3 | 57.00 | $15.39 |
| Wheels Pack | 1 | 78.00 | $21.06 |
| Servo Extension Cables | 1 Pack | 59.00 | $15.93 |
| Glue Gun + Sticks | 1 | 49.00 | $13.23 |
| Craft Knife | 1 | 45.00 | $12.15 |
| Soldering Iron Kit | 1 | 106.00 | $28.62 |
| Velcro Tape | 1 | 42.00 | $11.34 |
| Hobby Tape | 1 | 28.00 | $7.56 |
| SQ11 Mini Camera | 1 | 42.00 | $11.34 |
| MicroSD Card | 1 | 89.00 | $24.03 |
| **TOTAL** | **20 Items** | **SAR 1,847** | **$496** |

*Note: Direct purchase links are available in the repo's BOM.csv file.*

---

## Step-by-Step Construction Guide

### Phase 1: Preparation & Workspace Setup
1. **Prepare Workspace:** Clear a flat workbench, plug in your hot glue, and gather your craft knife, cutting mat, steel ruler, and soldering iron kit.
2. **Print & Assemble Plans:** Open the 2D template files, and print them with a Tile Scale of 100% (THIS IS IMPORTANT), across A4 sheets. Then align the grid marks, tape them together, and cut out the paper shapes.

### Phase 2: Cutting & Prepping Foamboard
1. **Trace Patterns:** Lay the paper templates onto your foamboard sheets and pin them on with a toothpick. Lightly trace the outlines with a pencil.
2. **Mark Cut Types:** 
   * **Solid Lines:** Full cuts through foam and paper.
   * **Score Cuts:** Partial cuts through top paper layer only for folding.
   * **Bevel Lines:** 45° angle scrapes for control surface hinges and wing edges.
3. **Cut Components:** Use a fresh craft knife blade held at a low angle along a steel ruler to make crisp cuts without tearing the foam. :)

### Phase 3: Airframe Assembly
1. **Build Fuselage Box:** Score-cut fuselage fold lines, run hot glue down the internal joints, fold the sides upward to form the box cargo fuselage, and then reinforce the inner bottom keel with a bamboo skewer.
2. **Construct Wing & Spar:** Glue a double-layered foamboard spar that's reinforced with a bamboo skewer at the spot where the wings will be. Fold the top foam skin over, and the glue down the trailing edge. Slide the wing through the fuselage center cutout and glue it on there securely.
3. **Attach Tail Assembly:** Glue the horizontal and vertical stabilizers onto the rear tail boom. MAKE SURE they're perfectly square (90°) to the wing plane!!!@@


### Phase 4: Electronics & Propulsion Installation
1. **Solder Harnesses:** Solder bullet connectors between motors and flight computers, and solder both power leads in parallel to a single battery connector.
2. **Mount Hardware:** Secure the twin motor mounts onto the wings, and install the 3 retractable landing gear bases onto reinforced mounting plates under the wings and nose.
3. **Control Linkages:** Install baby servos into their pre-cut pockets, mount control horns onto the control surfaces, and then connect pushrods with clevises set to neutral positions.


### Phase 5: Final Setup & Pre-Flight Check
1. **Receiver & Camera Setup:** Connect all 10 channels to the receiver and mount the action camera in the nose section. MAKE SURE ITS CONNECTED TO A STORAGE DEVICE.
2. **Center of Gravity (CG) Balancing:** Place the battery in the nose bay, support the aircraft on your fingers at where the wings are, and adjust the placement of all the components until the plane balances perfectly level.
3. **Pre-Flight Test:** Power on the transmitter first, connect the flight battery, and verify that all control surfaces move in the correct directions relative to stick inputs.

then fly weee

---

## Repository Structure

```text
├── README.md             # Complete project documentation and guide
├── BOM.csv               # Complete Bill of Materials with purchase links
└── media/                # Build photos, schematics, and flight footage
