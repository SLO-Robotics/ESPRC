# DIRECT ESP TO ESP RC. For Cars, Trucks and Robots!

<b>No WiFI needed! Ues ESP8266/32 as Remote and Recevers to control RC Cars, Trcuks and Robots</b>
<br>
By: Shane Weddle of SLO Robotic
<br>
First Build: 1/16/2021
<br>
Last Update: 3/5/2021
<br>
<br>
This Repo provides code for direct ESP to ESP communications using the built-in 2.4ghz radio to control RC Cars, trucks, Robots. 
<br>
To do this we make use of the ESP-Now features and library, ESP-Now makes use of WiFi management packets but you do not need to set up a WiFi SSID nor connect to a WiFi AP.
<br>
The MAC address of the receiver(slave) is all we need to know and the code that runs on the receiver will print its MAC. 
<br>
We then add that mac address to the remote(master).
<br>
The remote(Master) ESP can have multiple inputs. The basic two are potentiometers, one for speed and one for steering.
<br>
 - More inputs/sensors can be added. such as a button for applying the brake, or execute code to make the RC perform different functions.
<br> 
<b>FUN!</b> I have added 5 Buttons and have code that makes the RC truck do things like:
<br>
Button 1) Break! Motorcontoler break is on as the button is pushed.
<br>
Button 2) Full Stop! sets the break on the motor controler for 2 sec.
<br>
Button 3) Stop and turnaround.
<br> 
- (a) Sets break for 2 sec.
<br>
- (b) Set steering full left.
<br>
- (c) Backup 2 sec.
<br> 
- (d) Set steering to strait.
<br> 
- (e) Move forward 1 sec.
<br>
Button 4) Full speed 3 sec (good for jumps and straightaways)
<br>
Button 5) Strait!, sets steering to strait for 2 sec.
<br>
<br>

