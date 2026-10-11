## I made a Toadie! A Toad-shaped Starbie!
<img width="738" height="450" alt="Screenshot 2026-10-11 193304" src="https://github.com/user-attachments/assets/5699bd1b-86b8-40c1-82c3-1d789ae127b7" />

I first downloaded the care package provided by Half-Life! 
Then I watched No. 3: Installing symbol libraries, footprints, and 3D step files in Kicad 9video by Electronicx on YouTube to figure out how to download the schematics and footprints file from the guide. I had absolutely no idea before I started this endeavor about how one makes a circuit, so this was a totally new world to me, and the guide was very useful. 

## The Schematics
<img width="729" height="453" alt="image" src="https://github.com/user-attachments/assets/8723d8d8-7fc4-442a-b8ab-806476c4f577" />

So, following the guide, I uploaded the files AND got it working. 
### To upload components, click the letter A
This will allow you to choose components like sensors or boards. For this specific one, we used a XIAO-ESP32-C3
<img width="926" height="551" alt="image" src="https://github.com/user-attachments/assets/38896640-bd12-4d39-857c-96465c06a6ed" />
### To upload power symbols like gnds and volts batter, click the letter P
<img width="537" height="407" alt="image" src="https://github.com/user-attachments/assets/f2ad5c7a-4be0-41a3-a182-44d7438e2526" />
This will allow you to make connections.
### To name or raher precise how certain parts will be soldered or connected, click the letter L
<img width="820" height="457" alt="image" src="https://github.com/user-attachments/assets/d32f82df-1d30-4eb2-b683-ae572229d5ee" />

Since Starbie is a handheld digital pet, we need more than just the motherboard. 
### Components
<li>2 Buttons </li>  
<li>a DHT11 Environmental Sensor </li> 
<li>an OLED </li>
<li>and an MPU5060</li>

Wire them like this
<img width="729" height="453" alt="image" src="https://github.com/user-attachments/assets/8723d8d8-7fc4-442a-b8ab-806476c4f577" />

### Assign Footprints 
<img width="366" height="108" alt="image" src="https://github.com/user-attachments/assets/7c84c6be-4fcb-4fa7-a80d-66d6aa39bcdc" />

It should lead you to a pop up like so, match the sensors like
<img width="593" height="290" alt="image" src="https://github.com/user-attachments/assets/e9e406f4-4dd6-4bc5-8405-7bfae5500420" />

##  THE PCB
Once all the components are connected, we can start assigning footprints to the symbols we have here. Footprints are what get physically drawn on the PCB. To do this, click the "run footprint assignment tool" in the top right.
<img width="766" height="467" alt="Screenshot 2026-10-11 193250" src="https://github.com/user-attachments/assets/c7e0d5a2-7ab6-435f-b7e7-427a1088d089" />


To make the PCB, you can actually just convert your schematic into the alignment parts by clicking on the <img width="285" height="56" alt="image" src="https://github.com/user-attachments/assets/b819bb4b-2d21-45d7-b39e-863f1d3f7d73" />
This allows you to work directly on your PCB! Then you need to come up with the shape of your board. I wanted mine to look like Toad, but I suck at drawing, so I used to Reference images options:
<img width="417" height="420" alt="image" src="https://github.com/user-attachments/assets/7a448919-67cd-4dc2-a32e-778d9586156b" />
<img width="431" height="287" alt="image" src="https://github.com/user-attachments/assets/3553df17-b4eb-4f05-a05e-28fdd30a249b" />
Then, using the edge cuts on layers, you can then use the draw polygons to draw the approximate shape of your board.
<img width="390" height="271" alt="image" src="https://github.com/user-attachments/assets/08334fe3-625f-400b-a218-1a8e818b277b" />

Then you need to route your PCB so that all the connections are linked. To do that select the F.cu  layer
<img width="168" height="295" alt="image" src="https://github.com/user-attachments/assets/c0173e7f-4697-4f0c-834c-24af6c2aa410" />
Then click on any blue lines to fill them. You can also click on F for  the connections to be filled

### DRC (or Design Rules Check) is a tool that automatically checks for PCB design mistakes, such as disconnected traces or other various errors.

You can access it via the button on the top right:
<img width="300" height="71" alt="image" src="https://github.com/user-attachments/assets/a0a6194f-510a-439e-af4d-07f6a5780db0" />

Then click on run DRC to run the analysis 
<img width="772" height="485" alt="image" src="https://github.com/user-attachments/assets/059ebbdf-31a0-434c-a4e2-262b975efaee" />

To have access to the 3d render clink on this:
<img width="578" height="64" alt="image" src="https://github.com/user-attachments/assets/d9e27107-6ffc-4bc9-8541-c1e3fc894031" />

## DONE DONE DONEE
<img width="561" height="410" alt="image" src="https://github.com/user-attachments/assets/e5b3c491-52c6-4693-8599-403334bf9c56" />

