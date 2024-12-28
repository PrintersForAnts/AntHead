# AntHead
Toolhead for Micron and other PFA printers (Can also work on bigger 2020 based printers with the carriages linked below)
![image](https://github.com/user-attachments/assets/46479fa7-f2ea-4e98-a73c-22cb5ffeb9c2)

## BOM 
* 2x 4010 blower fans 
* 1x 2510 axial fan 
* various m3 hardware 
* BMG extruder kit , or G2 extruder kit (HGX variant is planned)
* Dragon Compatible hotend, Revo Voron, Rapido, TZV6 with or without v6 nozzle
* NOTE: if using a TZV6 hotend with the stock nozzle (small bambu style nozzle) you need to use the dragon hotend mount


when mounting the fans, the front cover needs to be removed prior to screwing it down with 2 m2x6 
![20240921_213730](https://github.com/user-attachments/assets/ab1f8089-46a0-4112-9aae-a728964323fd)

What Carriage Do I Print?


Printer  | Rail 
 ----|----|
Micron/SF/Pandora | Stock [MGN9H](https://github.com/PrintersForAnts/Micron/blob/main/STLs/Gantry/Toolhead/MiniSB/MiniSB_x_carriage_MGN9H_x1.stl) | 
Micron/SF/Pandora | Stock [MGN9C](https://github.com/PrintersForAnts/Micron/blob/main/STLs/Gantry/Toolhead/MiniSB/miniSB_x_carriage_x1.stl) |
Micron/SF/Pandora | Chirpy  [MGN9H](https://github.com/chirpy2605/voron/blob/main/general/Alternative_Voron_Mounts/Modified_Mounts/Micron_Pandora/STLs/X_Carriage_MGN9H_Micron_Long.stl)
Micron/SF/Pandora | Chirpy [MGN9C](https://github.com/chirpy2605/voron/blob/main/general/Alternative_Voron_Mounts/Modified_Mounts/Micron_Pandora/STLs/X_Carriage_MGN9C_Micron_Long.stl)
V0 | Stock works but i recommend Chirpys that can be found [here](https://github.com/chirpy2605/voron/blob/main/general/Alternative_Voron_Mounts/Modified_Mounts/v0.2) 
V2/Trident | Chirpys DB [MGN12H](https://github.com/chirpy2605/voron/tree/main/general/Alternative_Voron_Mounts/Modified_Mounts/V1_V2/STLs/MGN12H)
V2/Trident | Chirpys DB [MGN9H](https://github.com/chirpy2605/voron/tree/main/general/Alternative_Voron_Mounts/Modified_Mounts/V1_V2/STLs/MGN9H)



## Future Plans ##
* HGX Based extruder
* Revisit BMG based extruder
* Bowden option
* Filament cutter (in beta on discord)
* larger variety of hotend mounts

## Change log ##

### 10-30-2024
* Updated CAD to v29
* missed exporting latest right fan ducts from previous commit, they worked but had an extra chamfer that needed to be removed  

### 10-29-2024 #2
* modified main housing to now support Sherpa bolt pattern as well as Orbiter 2 bolt pattern
* ducts were updated to fit the latest change
* a Base Grill cad file was uploaded so custom grills can be made 

### 10-29-2024 #1
* Fixed an issue that was introduced with the latest LED changes from 10-28
* updated main housings, and Cad file

### 10-28-2024
* Updated assembly to v20
* Updated the LED to use the same style as Stealthburner that inserts from the bottom 
* Fixed orientation of various files 

### 10-17-2024
* Added latest CAD assembly
* removed recesses in main housing as they arent needed anymore since hotend mount screws are recessed into the printed part
* added a Voron logo variant of the main body 
* added LED logo parts for both Micron and Voron logo 
* added a dual filament sensor WWG2 variant extruder as the default extruder option in CAD 
* organized files a bit more
