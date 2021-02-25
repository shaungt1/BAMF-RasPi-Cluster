# Instructions: 
Please follow this instructions this is the build method I used feel free to print these in your own way. This is just what worked best for me have fun!

### BILL OF MATERIAL 

**3D PRINT**
- [x] R-LID
- [x] L-LID
- [x] R-CASE
- [X] L-CASE 
- [X] TOP-RASPI-RACK (Has No male adapter ends both side female 4mm hole) 
- [X] RASPI-RACK 
- [X] HDD-RACK
- [X] SSD-RACK
- [X] 4 X FRONT CLIP 
- [X] 1 X BACK CLIP 

**WHAT YOU WILL NEED TO GET** 
- [ ] RASPIS AND GEAR 
- [ ] 3.5/4in touch screen for Raspi 
- [ ] 2-120mm CPU RGB FANS
- [ ] JB WELD EPOXY 
- [ ] 10 3/4 L SCREWS 4mm DIA 
- [ ] 4 1/4 L SCREWS 4mm DIA 

<hr/>


**From Inside to Outside:** 

#### FRONT CLIPS 
 Print the FRONT_CLIP file it has 3 extra clips you will need later. After the housing is printed you will use the front and back clips with the epoxy to seem together the housing into 1 piece. 

Note: 
You can also fill the slice regions on the bottom and back with epoxy to make a more solid unit. 

**The front section of the case requires acrylic or glass plate 1.5mm or 2mm thick x 118mm x 215mm +- 10% tolerance that will slide through the top slit on the front of the housing.** (you can cut down a poster frame acrylic front cover like I did or use glass)

#### BACK CLIP 

This clip will be used with 2 1/4 screws to tie together the housing from the back of the unit based on the 2 hole marks.

#### HDD & SSD RACKS 

The entire unit can hold 1 HDD rack  (is 35% taller than SSD)  and 2 SSD racks or total of 3 SSD racks. Simply print the desired racks you want and clip them together when you are done. 

*Note:* After the Housing united is printed use 4-3/4 screws to screw the bottom rack dead center. this will also server to tie together the separate housing units. Do this step first before assembling anything else.


#### RASP-PI RACKS 

Simply print 2 RASPI racks and 1 TOP-RASPI rack. The top RASPI rack has female ends on the bottom and top so it can adapt to the RASPI rack below it and  use 4 3/4 screws to tie the lids assembly together. 

#### CPU RGB COOLING

After printing the above parts and acquiring the 2-120mm RGB CPU fans you will need to print the  **CE3_RAILS.gcode** file this is the tower railing system that uses 3/4+ inch screws to mount the fan to the railing system and to the RASPI and SSD or HDD cases.  

Note: If you do not want to use epoxy to mount the railing system to the RASPI and SSD/HDD racks do that first then mount the 2 CPU RGB fans. Typically the RGB fans come with 1.5in mounting screws you may also use these.

#### HOUSING 
Print these parts last!!! 
There is an outer shell housing is in 2 parts labeled that must be printed separately if you are using and ender 3 or ender 3 pro you will need to find the "creality_ender3.def.json file 

*Windows:*
in path:  **Program Files / ultimaker Cura 4.6(or whatever version..) /resources . definitions...** 

Replace the**machine disallowed_areas** array to an empty array within the object it should look like this when you are done: 


**Before:** 
![Before edit](https://github.com/shaungt1/rasp-Pi-Dev-Creator-Battlestation/blob/main/3D%20BAMF%20Rack%20File/ANIMATION/img/before.png)



**After:** 
![After edit](https://github.com/shaungt1/rasp-Pi-Dev-Creator-Battlestation/blob/main/3D%20BAMF%20Rack%20File/ANIMATION/img/after.png)

This is to give you the full bed print area of 220mm and not get stuck with the limitations Cura and other 3D printers puts on your printer. You can apply this change to any *def.json* file to match your printer. 


## BAMF Rack Case Assembly instructions

- Print all parts 
- Clip together all HDD, SSD, RASPI Rack and TOP-RASPI racks. 
- Place rails over the racks and mount to racks 
- Mount 2 RGB CPU Cooling fans (as per instructions) 
- Mount entire assembly to the 2-pieces housing  by screwing the bottom screws into the HDD or SDD bottom rack. 
- use epoxy to seal housing assembly together 
- Mount front clip to the back of the Housing assembly on the top front section with epoxy covering the seems. 
- Mount back clip to the back of the Housing assembly on the top front section with 2 1/4in screws reinforced with epoxy covering the seems. 

## Gear Assembly 
- Prepare raspis as shown in the videos
- Add all external HDD/SSD units with usb power cables to designated PIs 
- mount the CPU fans to the digital I/O pins on the first RasPi unit 
- mount the touchscreen to the top raspi in the 4in opening. 

Cheers! 

You are now the proud owner of a... 

#### Bad / A** / Multi-server / File-server-system**

If you have any questions or any new mod go to my channel and drop me a message here: 

**@ShaunP** 
https://www.youtube.com/channel/UC78cpbnaq-eeKGGHIEtUgdw


