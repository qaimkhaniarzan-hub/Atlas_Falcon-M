# Atlas X Falcon-M
Welcome to my project. This readme includes:

-> An overview of both projects, and how they are integrated together

-> A guide to this repository, Including what's In it, and where it is

-> A guide to reproducing my work

-> Background information about this project and why it exists

-> Mission Sequence


# 1.**Overview**
**Atlas**

Atlas is a mid-sized, radio-controlled cargo aircraft, completely built from scratch. Its purpose in this project is to take off, reach a suitable altitude, deploy Falcon-M when required, maintain stability despite losing the payload's mass, and land safely.

Atlas is the carrier aircraft and the primary platform responsible for transporting Falcon-M. It must be designed to accommodate the additional payload weight without compromising its flight characteristics, structural integrity, or ability to land.
**Falcon-M**
Falcon-M, short for Falcon-Mini, is a bulbous-shaped hybrid between an air-propelled drone and an autonomous lander.

Its intended purpose is to safely separate itself MIDAIR from Atlas, automatically reorient itself, and descend towards a designated landing zone. During its descent, it will attempt to control its orientation and trajectory before performing a landing burn to reduce its velocity enough for its landing gear and suspension system to absorb the remaining impact.

This project requires both systems to communicate as per altitude, relative velocity, and small adjustments like Atlas gaining altitude for a few meters as separation occurs. 

# 2. **Guide**

In the repo's Root, there are 4 key files/folders

>This readme

>Atlas's Folder

>Falcon-M's Folder

>Joint folder

Each vehicle has its own dedicated engineering files, while the joint folder contains information relevant to the overall system.

Both the ATLAS/ and FALCON-M/ folders contain the following directories:


BOM: Bill of Materials, listing the components, quantities, specifications, and costs.

Calculations: Engineering calculations, measurements, estimates, and supporting mathematical work.

Testing: Test procedures, results, photographs, observations, and revisions.

Electronics: Electrical architecture, components, wiring, sensors, controllers, and power systems.

CAD: CAD models, design references, technical drawings, and exported models.

Documentation: Project-specific documentation, design explanations, and technical notes.

The purpose of separating these directories is to keep the engineering work organised and make it easier to track development.

# **3. Reproducing This Project**

This section is intended to help someone understand the project and reproduce its engineering work.

>The project is being developed incrementally. Not every design or system is complete, and some sections may contain preliminary designs, calculations, or simulations rather than verified physical results.

To reproduce the work:

Clone or download this repository.

Read this README to understand the overall mission and the relationship between both vehicles.

Read the individual project README files in ATLAS/ and FALCON-M/.

Review the relevant CAD files, calculations, and component lists.

Follow the documentation and testing records for each development stage.

Compare any reproduced results against the recorded measurements and observations.

**Software and tools**

The specific software and tools used will be documented within their respective project folders.

Where applicable, individual files should include their software version, dependencies, units, assumptions, and instructions for opening or running them.

Reproducibility principle: Designs, calculations, and test results should be documented sufficiently for another person to understand what was done, why it was done, and how the results were obtained.

#**4.Background**

I started this project because of my love for aviation. Ever since i was a little tiny ostrich egg, i loved planes a lot. I want to be a plane when i grow up. Thus, i wanted to make a plane, but i have no money cuz im just an ostrich. I then started this project as a rough mess in hack club stardance, but had no motivation to finish it and no actual funding cuz there were so many ppl. Now, I'm continuing Atlas, the original project, with a side project Falcon-M, for fallen. I have the motivation since i really wanna go to the live event, and i hope to get the funding too from hack club fallen. I hope to learn alot from this project, like aerospace design roadmaps, how much testing u really needa do b4 building smth, and how to actually make my first working hardware project. I hope you have as much fun building this as i have.

#**5.Mission Sequence**
The following describes the intended mission. It is a target operational sequence, not a claim that the complete system has already been built or tested.

**Phase 1 — Ground preparation**

Inspect Atlas and Falcon-M.

Verify their respective electrical and mechanical systems.

Check the payload retention interface.

Confirm battery status and system readiness.

Verify the intended landing zone and mission conditions.

**Phase 2 — Atlas takeoff**

Atlas takes off under radio control.

The aircraft climbs to a predetermined operating altitude.

The carrier aircraft establishes a suitable flight condition for the intended separation.

**Phase 3 — Payload separation**

Atlas releases Falcon-M through its payload mechanism.

Falcon-M separates from the carrier aircraft.

Atlas makes any required flight adjustments to maintain stable flight.

Falcon-M begins its independent stabilisation sequence.

**Phase 4 — Falcon-M stabilisation**

Falcon-M determines its orientation using its onboard sensors.

Its control system attempts to correct unwanted rotation.

The vehicle establishes a suitable descent attitude.

Its navigation system begins estimating its position relative to the intended landing zone.

**Phase 5 — Controlled descent**

Falcon-M continues descending towards the landing zone.

Its control system evaluates its orientation, velocity, and position.

Propulsion(Via electronic props) and trajectory-control methods are evaluated to achieve a controlled descent.

**Phase 6 — Landing**

Falcon-M attempts its final landing manouver

Its propulsion system reduces descent velocity.

The landing gear and suspension absorb the remaining impact.

The vehicle comes to rest within the designated landing zone.

**Phase 7 — Atlas recovery**

Atlas continues its independent flight after separation.

The aircraft returns to its designated landing area.

Atlas performs a normal landing.

**Phase 8 — Post-mission analysis**

Review the mission data and recorded measurements.

Compare actual performance against simulation predictions.

Identify failures, limitations, and unexpected behaviour.

Document proposed improvements for the next revision.

**Thats it! I hope this README provided a thoughtful and detailed approach so that YOU understood what i meant to do here, and how its meant to work! Thanks for reading!**


