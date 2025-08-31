---
Title: "Simple NFC Business Card"
Author: "Tak-min" 
Description: "A self-made, credit card-sized NFC business card that shares contact info with a tap." 
Created On: "08/27/2025"
---

---
August 27th: Project Start!
I'm starting a project today!
My goal is to create a PCB business card that can send a self-introduction webpage to a smartphone via NFC!
I looked into possible chips that I could use, and it seemed like the NTAG series chip would be a good choice! This is because I saw them being used frequently when I was looking up information on YouTube and other sites!

[image1.png]

Total time spent: 3h
---

---
August 28th: Antenna Calculations & Circuit Design
We've focused on the most important component: the antenna! 
We've calculated the inductance of the NFC antenna so that the circuit will operate at 13.56MHz and fit into a 91mm x 55mm business card size!

Total time spent: 4h
---

---
August 29th: Completed the Schematic in KiCad
I've turned yesterday's design into an official schematic!
The schematic is pretty simple, just including the NFC chip, PCB trace antenna, and a few other little decorations!
Now I just need to create the BOM...

[image2.png]

Total time spent: 3h
---

---
August 30th: Started PCB Layout and Component Placement
We've moved from schematics to actual board design! 
We've created a PCB project and created the outline with edge cutting! We're making great use of chip footprints and silkscreens to create something amazing!

Total time spent: 5h
---

---
August 31st: Finished Routing and Passed DRC!
The most difficult part, wiring the antenna coil, is now complete!
Carefully route the copper foil pattern for the antenna, carefully matching the inductance!
Once the routing is complete, run DRC to make sure there are no manufacturing violations!
It took a long time, but the board generation is now complete!

[image3.png]

Total time spent: 6h