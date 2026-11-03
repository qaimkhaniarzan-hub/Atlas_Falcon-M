\# Atlas Airfoil Definition — Version 1.0



\*\*Project:\*\* Atlas RC Cargo Aircraft

\*\*Subsystem:\*\* Main Wing

\*\*Document ID:\*\* ATLAS-AERO-AIRFOIL-001

\*\*Version:\*\* 1.0

\*\*Date recorded:\*\* 3 November 2026

\*\*Status:\*\* Initial geometry definition — aerodynamic validation pending



\## 1. Purpose



This document records the airfoil geometry selected for the Atlas main wing. It preserves the Blender generator settings so that the profile can be reproduced, analysed, and compared against future design revisions.



\## 2. Airfoil identification



| Property                      | Value        |

| ----------------------------- | ------------ |

| Airfoil family                | NACA 5-digit |

| Generated profile designation | NACA 25111   |

| Design lift coefficient       | 0.30         |

| Maximum camber location       | 25% of chord |

| Maximum thickness             | 11% of chord |

| Reflexed profile              | No           |



\## 3. Blender generation settings



| Setting                    | Value                          |

| -------------------------- | ------------------------------ |

| Generator                  | Blender Airfoil Selection tool |

| Mode                       | NACA 5 digits                  |

| Points                     | 101                            |

| Cosine points distribution | 0.50                           |

| Fill surface               | Enabled                        |

| Generator chord            | 1.00                           |

| Construction plane         | Y-Z plane                      |



\## 4. Relationship to Atlas wing geometry



The previously recorded Atlas wing dimensions are:



| Dimension     |    Value |

| ------------- | -------: |

| Full wingspan |  1.430 m |

| Root chord    |  0.142 m |

| Tip chord     | 0.0596 m |



The generator chord setting of 1.00 is not being treated as the physical wing chord. The airfoil profile must be scaled to the appropriate local chord when incorporated into the wing.



\## 5. Design rationale



The NACA 25111 profile is the current selected airfoil geometry for the Atlas wing.



Its aerodynamic suitability has not yet been established. The profile must be analysed at representative Reynolds numbers and angles of attack before we make claims about lift, drag, stall behaviour, or flight performance.



\## 6. Verification still required



\- \[ ] Export the generated airfoil coordinates.

\- \[ ] Confirm the exported profile matches the NACA 25111 designation.

\- \[ ] Verify leading-edge and trailing-edge geometry.

\- \[ ] Confirm the airfoil is correctly oriented on the wing.

\- \[ ] Confirm the root and tip sections use the intended profile.

\- \[ ] Analyse the profile using XFLR5 or another suitable aerodynamic tool.

\- \[ ] Record lift and drag polars.

\- \[ ] Record the analysis conditions and software version.



\## 7. Evidence



\*\*Original evidence:\*\* Blender Airfoil Selection screenshot, captured 3 November 2026.



The screenshot shows the generator parameters and the generated profile designation. SS to be preserved.



\## 8. Revision history



| Version | Date       | Changes                                                   |

| ------- | ---------- | --------------------------------------------------------- |

| 1.0     | 2026-11-03 | Initial airfoil definition recorded from Blender settings |



\---



\*\*Engineering note:\*\* This document records the geometry-generation settings, not experimentally verified aerodynamic performance. All performance conclusions must be supported by calculations, simulation, or physical testing.

