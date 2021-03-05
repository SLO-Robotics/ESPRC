# Welcome to GitHub Desktop!

<b>Direct ESP to ESP (no wifi) Using ESP32 or ESP8266 Remote Control for RC Cars, Trcuks and Robots</b>
<br>
By: Shane Weddle of SLO Robotic
<br>
First Build: 1/16/2021
<br>
Last Update: 3/5/2021
<br>
<br>
This Repo provides code for direct ESP to ESP counications using it's 2.4ghz radio to controle RC Cars, trucks, Robots. 
<br>
This done with the help of the ESP-now libreay, This libreay makes use of wifi mangemnt packets but no need to connect or setup wifi. All that is needed is the MAC address of the receevers(slave). 
<br>
The code once loaded on to a recever esp will print its MAC to the searil port at boot. We then add that mac address to the remote.
<br>
The Remote(Master) ESP can beconnected to multabel inpputs, the basic 2 are one potencheometer for speed and one for sterang.
<br>
But more inputs/senseors can be added. such as a button to make a break, or exacute other code to make the RC preform difrent functions.
<br> 
<b>FUN THINGS!</b> I have added 5 Buttons and have code that makes the RC truck do things like:<br>
Button 1) break! Motorcontoler break is on as button is pushed.
Button 2) Full Stop! sets the break on the motor controler for 2 sec.
Button 3) Stop and turn araond.<br> 
- (a) Sets break for 2 sec.<br>
- (b) Trun whell.<br>
- (c) Backup 2 sec.<br> 
- (d) strat wheel.<br> 
- (e) Move forward 1 sec.<br>
Button 4) Full speed 3 sec (good for jumps and strataways)
Button 5) Strait!, sets stearing to strait for 2 sec. 

I got into this buying 2 crappy RC cars from Target for me kids, they diid not last long and the 
