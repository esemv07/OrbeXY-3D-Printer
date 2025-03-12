Made by: @esemv

Repository link: https://github.com/esemv07/OrbeXY-3D-Printer

Total hours so far: 24 hours

- [x] I have a 3D printer or will be getting one before March 21st

## Day 1: March 8th 2025 
`Reseach` `PCB` `CAD`
- I reseached materials and what would be compatible with each other while staying in budget and my size constraints. I decided on an Extuder (Obbiter V2.0), and a Motherboard (BigTreeTech SKR Mini E3 V3.0). 

- I found a potential option for a printbed. It is quite difficult to find one that is in the correct size (100x100mm) as most come in 120x120 for the smallest size. I have decided that for the PEI Plate, I will buy a bigger size and cut it to the correct dimensions myself.

- I then designed a quick and simple PCB for the small Optical Endstop Sensors that I can use to keep the printhead in build area for all axes.

`Research: +3 hours` `PCB: +1 hour`

***+4 hours***

- I also researched different methods of multicolour printing and what would take up less space. Started designing a PCB for a Rotary Switcher Multi Material System, but then realised it would be to big for my printer size. I settled on using an MMU but I think I will design that last so I get the core mechanics good first.

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/17dddf8e195e510be711aa119abce13b8c4cffe4_screenshot_2025-03-09_at_6.58.24___am.png" width="350" title="CAD Mockup">

- Started a rough CAD model in Fusion of the frame to visualise the dimensions. I may change the 2020 Aluminium Extrusions to 1010.

`Research: +1 hour` `CAD: +2 hours`

***+3 hours***

### Time Spent on This Day: 7 hours 
`Research: 4 hours` `PCB: 1 hour` `CAD: 2 hours`

<br><br>
## Day 2: March 9th 2025
`Research` `CAD`

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/99b705cbeaa3b43d16e4490dd5908a8b150a32d6_cad-09_03_2025.png" width="350" title="CAD Frame Reshape">

- I reshaped the frame so that there was more space on the inside and it will be less confusing for physical connection when I build it. It is now 200mm<sup>3</sup>, using 8 x _2020 160mm Aluminium Extrusions_ and 4 x _2020 200mm Aluminium Extrusions_.

- I then researched power supplies - how they work, how to know what voltage, current, and wattage to use. I also researched different methods for the Z-Axis on a CoreXY printer. I figured out that due to the very small scale of my printer I won't need to support all 4 corners of the build plate.

- I also reasearched hotends and how to connect them to my extruder which is direct drive. I am going to design a 3D printable mount so I can connect my direct drive extruder (Orbiter V2.0) with my hotend (Short E3D V6 Hotend with PTFE).

`Research: +3 hours` `CAD: +30 mins`

***+3 hours 30 mins***

### Time Spent on This Day: 3 hours 30 mins

`Research: 3 hours` `CAD: 30 mins`

<br><br>
## Day 3: March 10th 2025
`Research` `CAD`

- I researched toolhead designs and what fans I could use for mine and how I could mount the extruder to the hotend.

`Research: +1 hour`

***+1 hour***

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/13e36eb811a0c3c0056467aa27a2fe0c9376ed16_screenshot_2025-03-10_at_6.23.23___pm.png" width="350" title="CAD Toolhead">

- I designed the toolhead with different parts that would mount together using screws and heatset inserts.

- There are 3 different parts: the part that mounts to the front of the hotend, the part that connects the axial fan to that part, and the part that mounts to the back of the hotend connecting the other fan and the extruder.

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/79dd78bd85854feea0189e9b24e4537d54ee480c_screenshot_2025-03-10_at_6.23.59___pm.png" width="350" title="CAD Toolhead in Assembly">

- Here is what it looks like in the full assembly so far.

`CAD: +3 hours`

***+3 hours***

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/a5a222bda7bdba1430c38d7a3bc90eaf84027b99_cad-10_03_2025-3.png" width="350" title="CAD Toolhead Angled">

- I also changed the angle of the side fan to blow the air more towards the nozzle and to optimise space on the toolhead.

`CAD: +1 hour`

***+1 hour***

### Time Spent on This Day: 5 hours

`Research: 1 hour` `CAD: 4 hours`

<br><br>
## Day 4: March 11th 2025

`Research` `CAD`

- I did more research on toolheads and realised that I need to add a channel for the air to flow towards the nozzle. I researched different methods of this for my design.

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/7733821186895e280088b18ef19c31b23e9dbf51_cad-11_03_2025-1.png" height="400" title="CAD Toolhead Airflow 1"> <img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/cf66ce6f001f85248d64ca577ed78a27648045b1_cad-11_03_2025-2.png" height="400" title="CAD Toolhead Airflow 2">

- I then applied this to my CAD model trying not to impede on the parts that I already had. This proved much harder than I expected and I had many iterations of it before I finally achieved a result that I wanted.

`Research: +30 mins` `CAD: +2 hours`

***+2 hours 30 mins***

### Time Spent on This Day: 2 hours 30 mins

`Research: 30 mins` `CAD: 2 hours`

<br><br>
## Day 5: March 12th 2025

`Research` `CAD`

- I researched the different axes motion systems and what motors and linear rails to use. I think I will use MGN7 rails and MGN7-H for the carriage and I will use NEMA 14 Stepper Motors. I still don't completely understand the belt system but I will model the rails and carriage connections first.

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/baa4b052f033cc7cbe6962d33defa073071a24bb_cad-12_03_2025-2.png" width="350" title="CAD Full Assembly">

- I then added the linear rails to my full assembly and realised that it would be better to go with MGN9 rails and MGN9-H carriages so I added them instead. This meant I had to change the connection on the toolhead to fit on the MGN9-H carriage.

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/43610adf80ba3613922e961b7cd26198cf9fb8a8_12_03_2025.png" width="350" title="CAD Full Assembly">

- I also had to model some connectors to connect the X-Axis linear rail to the Y-Axis rails so that they could move together. Here is what they look like.

<img src="https://hc-cdn.hel1.your-objectstorage.com/s/v3/43610adf80ba3613922e961b7cd26198cf9fb8a8_12_03_2025.png" width="350" title="CAD Full Assembly">

- I then put all the new and modified components together in the full assembly. Here's what it looks like to far!

`Research: +3 hours` `CAD: +3 hours`

***+6 hours***

### Time Spent on This Day: 6 hours

`Research: 3 hours` `CAD: 3 hours`

<br><br>
