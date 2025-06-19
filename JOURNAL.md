---
title: "Cuprite"
author: "Renovic"
description: "Ender 5 + to fixed gantry corexy with triple Z designed for fast printing"
created_at: "2025-06-10"
---

# Day 1 - Intial Planning
This day is more of an summary of my previous thoughts and plans for this printer. 
I have been somewhat planning this printer rebuild since I bought it a few months ago, so I have some components for it already, but haven't started a full CAD model yet.
 
The primary goal for this printer is fast PLA and ABS printing, and a platform I can expirement with true non-planar printing.

### Gantry
Although I initially wanted to just use a Voron Trident gantry, I found the Monolith gantry. Its much more rigid and has a shorter effective belt length for better input shaper graphs.
However, I don't have the capability of printing high temp enginnering materials, so I can't just use printed motor mounts without them melting over time. 
So, I am planning on redesigning it for CNCing some parts. I plan on using my school's CNC to do this, so it doesn't count towards the project budget. 

Parts I have
- Rails
- Belts
- Some Motors

Parts I need
- Bearings
- Pulleys
  
### Z Axis
I want to do a triple Z that can tilt to bed for future non planar printing. The example I found that looks rigid and precise is the Annex engineering K3's Z axis.
But its a belt driven Z, so its somewhat expensive. I already have leadscrews from the stock printer, so I decided on adapting K3 Z for leadscrews.

Parts I have
- Rails
- Leadscrews
- Motors

Parts I  need
- Bearings (For Maxwell coupling)
- Rods

### Toolhead
Currently I have a Peopoly Lancer Long hotend and the parts for a bmg extruder, but no good part cooling solution. 
On my ender 3 I am using the same parts with 2x 5015 fans for my cooling, but its too little cooling for fast print speeds.
So I want to use higher cfm cooling, either 3628 axial fans or an external 7075 CPAP Fan. 
Using a CPAP will be an intresting design challenge because I will have to optimize my ducts a lot more that I would for 5015s or 3628s. 

Recently I found the Monolith Gantry's creator tested a fully slm toolhead. It gave very good input shaper results since it was almost entirely one piece and supported the hotend near the bottom.
If I can somewhat replicate that design, and manage to keep it low cost, it would give very good performance (> 50k accel without any artefacts).

Parts I have
- Hotend
- Extruder

Parts I need
- Part cooling fans
  
### Other 

I have my frame mostly planned out, using a lot of the original ender 5 frame, but extending it in the x-axis for more travel and adding a top hat. 
For the electronics, I managed to get a cheap Fystec Spider and already have a raspberry PI, but I need to design the full electronics enclosure.

Parts I have
- Frame
- Mainboard
- Rasberry PI
- PSU

Parts I need
- Wiring 
- Panels
- Probably a lot of stuff I forgot


**Hours Spent: 3** 

# Day 2 - CAD started
Created a new frame using some of the extrusions from the base Ender 5. Primary goals of this frame is to maximize travel from using 400mm rails and still have space for large toolheads.
I then added the 9mm 2wd configuration of the Monolith gantry as a placeholder. Soon I'm going to modify it to add a strucural front brace and make it attach to the extra 2020 extrusions on the side and back rather than only the gantry extrusions.

I started planning the Z axis by placing the bed for keeping the most usable bed space. I only have some extra extrusion left over, so I'm figuring out the extrusions for the bed framing.

![Screenshot 2025-06-18 230845](https://github.com/user-attachments/assets/bde613d4-5830-4647-a391-a5f413e675f5)

**Hours Spent: 3**
**Total: 6** 
