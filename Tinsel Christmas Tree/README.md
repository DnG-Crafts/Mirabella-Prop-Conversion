# Pop-Up Flashing Tinsel Christmas Tree

a fairly easy conversion to wled for the <a href=https://www.mirabella.com.au/mirabella-product-item/pop-up-flashing-tinsel-christmas-tree/>Mirabella 1.5m Light Show Pop-Up LED Dome Tree</a><br>

each string has 13 pixels, there are 15 strings for a total of 195 pixels each pixel is individually addressable.<br>

the controller has 4 wires that are silkscreened.<br>

<b>+</b>  = 5v<br>
<b>-</b>  = GND<br>
<b>DO</b> = Data Out<br>
<b>L</b>  = GND to Star<br>

the connection to the ESP is simple...<br>
connect the 5V(+) to the 5V of the esp.<br>
Connect GND(-) to the GND of the esp.<br>
Connect Data Out(DO) to a GPIO of the esp, in my case i used GPIO13.<br>

in wled set the GPIO you used, color order is RGB and led count is 195.<br>

if you wish to light the star then connect (L) to the esp GND.<br>

<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/1.jpg><br>
<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/2.jpg><br>
<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/3.jpg><br>
<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/4.jpg><br>
<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/5.jpg><br>
<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/8.jpg><br>

## Star modification

if you wish to add pixels to the star you can repurpose the (L) wire as a data line to the esp, in my case i connected it to GPIO12.<br>
i replaced the leds in the star with 10 seed pixels.<br>

<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/6.jpg><br>
<img src=https://github.com/DnG-Crafts/Mirabella-Tree-Conversion/blob/main/Tinsel%20Christmas%20Tree/7.jpg><br>