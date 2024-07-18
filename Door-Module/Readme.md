# Door-Module
<p align="center">
  <img src="./images/Door-Module_L.png" width="400">
  <img src="./images/Door-Module_R.png" width="400">
</p>

<p align="center">
  <img src="./images/Door-Module.gif" width="800">
</p>

All provided files are in metric units (mm). The design is adapted to generic 30x30 Aluminum Profiles. For smaller profiles, the door panel cutout needs to be laterally shifted in order to fit the servo lever (a thinner profile would unmatch their relative orientation). The foldback clip was used to fix counterweights to the servo lever. All parts can pe either laser cut, 3D printed or hand sawed. The design aims at maximum reproduxibility with low total cost.

### File List

| Door-Module Component | Production Amount | Material |
| :---: | :---: | :---: |
| Arduino Holder | 1 piece | Acrylic glass 6mm, PLA or ABS |
| Counterweight | 4 pieces | Acrylic glass 6mm, PLA or ABS |
| Door Panel | 1 piece | Acrylic glass 6mm, PLA or ABS |
| Electronics Panel | 1 piece | Acrylic glass 6mm, PLA or ABS |
| Floor Rest | 2 pieces | Acrylic glass 6mm, PLA or ABS |
| Mock Floor | 1 piece, optional | Acrylic glass 6mm, PLA or ABS |
| Profile Stopper | 2 pieces | Acrylic glass 6mm, PLA or ABS |
| Servo Lever | 1 piece | Acrylic glass 6mm, PLA or ABS |

All files are available as .STEP (for 3D CAD), .DXF Files (scaling: 1pt equals 1mm for laser cutting), .STL (3D Object for Printing) and .SVG (Open Source Vector Graphic).


### Commercial Parts List

| Item | Quantity | Notes | Product Example Link |
| :---: | :---: | :---: | :---: |
| Arduino Nano | 1 piece | with pin headers | [arduino.cc](https://store-usa.arduino.cc/products/arduino-nano?selectedStore=us) |
| Whadda Servo MG995 | 1 piece | with mounting hardware | [whadda.com](https://whadda.com/product/servo-mg995-wpm603/) |
| BNC Connector | 3 pieces | with mounting hardware | [digikey.com](https://www.digikey.de/de/products/detail/amphenol-rf/31-221-RFX/100648) |
| Aluminum Profile 30x30 mm | 2 pieces 500 mm | length de | [us.rs-online.com](https://us.rs-online.com/product/bosch-rexroth-assembly-technology/3842990720-1000mm/73548689/) |
| CRC Food Grease | 1 spray can | anti-friction | [crceurope.com](http://www.crceurope.com/crc/CRCproductdetail.csp?division=industry&product=FG) |
| USB-A to USB Mini-B Cable | 1 piece | power delivery and coding | [digikey.com](https://www.conrad.de/de/p/dsg-canusa-8640015953-schrumpfschlauch-ohne-kleber-schwarz-1-60-mm-0-80-mm-schrumpfrate-3-1-10-m-708870.html) |
| Shrinktube 1.6 - 0.5 mm 3:1 shrinkratio | 20 cm |  | [conrad.de](https://www.conrad.de/de/p/dsg-canusa-8640015953-schrumpfschlauch-ohne-kleber-schwarz-1-60-mm-0-80-mm-schrumpfrate-3-1-10-m-708870.html) |
| Jumper Cables | 7 pieces |  | [conrad.de](https://www.conrad.de/de/p/renkforce-jkmf403-jumper-kabel-arduino-banana-pi-raspberry-pi-40x-drahtbruecken-stecker-40x-drahtbruecken-buchse-30-2299844.html) |
| Foldback Clip 19 mm | 1 piece | for fixing counterweights | [conrad.de](https://www.conrad.de/de/p/rapesco-foldback-klammern-breite-19-mm-schwarz-65800180-804794934.html) |
| Low-Profile T-Nut M6 | 4 pieces |  | [conrad.de](https://www.conrad.de/de/p/schneider-electric-nsynm6-nsynm6-gleitmutter-m6-stahl-100-st-1876707.html) |
| Screw M6 x 16mm | 6 pieces |  | [conrad.de](https://www.conrad.de/de/p/839601-innensechskantschrauben-m6-16-mm-innensechskant-stahl-verzinkt-100-st-839601.html) |
| Washer M6 | 6 pieces |  | [conrad.de](https://www.conrad.de/de/p/rs-pro-unterlegscheiben-fuer-m6-schrauben-a4-316-b-form-0-8mm-x-6-4mm-x-12-5mm-edelstahl-packung-a-50-stueck-900765647.html) |
| Screw M3 x 16 mm | 8 pieces |  | [conrad.de](https://www.conrad.de/de/p/toolcraft-839705-zylinderschrauben-m3-16-mm-innensechskant-din-912-edelstahl-a2-100-st-839705.html) |
| Washer M3 | 8 pieces |  | [conrad.de](https://www.conrad.de/de/p/rs-pro-unterlegscheiben-fuer-m3-schrauben-glatt-a2-304-flach-0-5mm-x-3-2mm-x-7mm-edelstahl-packung-a-250-stueck-805559965.html) |
| Nut M3 | 8 pieces |  | [conrad.de](https://www.conrad.de/de/p/toolcraft-131880-sechskantmuttern-m3-din-934-stahl-100-st-131880.html) |



Lasercutting
--------------------

We used a Trotec Speedy Flex lasercutter with a 100W CO2 laser with the following settings:

| Parameter | Cutting Quality | Engraving Quality (Arduino Holder) |
| :---: | :---: | :---: |
| Power | 70 % | 70 % |
| Speed | 0.2 % | 3.5 % |
| Laser Source | CO2 | CO2 |
| Frequency | 20'000 Hz | 1'000 Hz |
| Passes | 1 | 1 |
| Power Correction | 10 | 10 |
| z-Offset | -2 | 0 |
| Resolution | N.A. | 500 DPI |

3D Printing
--------------------
We suggest printing with PLA, tough PLA or ABS for best results. Any standard print settings will provide aceptable results. Avoid fancy materials to reduce cost and effort.


Wiring Diagram
--------------------
Connections and an image or so


