<h1>Palo Alto Firewall Factory Reset</h1>


<h2>TLDR Description</h2>
Factory reset of a Palo Alto 220 Firewall  
<br />

<h2>Purpose</h2>
The purpose of this lab is to factory reset a Palo Alto 220 Firewall to begin the upcoming configuration labs with a clean slate, this could translate to the professional world in the context of implementation of second hand equipment or a wipe of out of favor equipment.
<br />

<h2>Background Info</h2>
The firewall we are working on in this lab, the Palo Alto 220 Firewall, was released in 2017 and was widely respected throughout the tech industry but as of recently it has slowly faded giving room to newer, improved firewalls.
<br />

<h2>Lab Summary</h2>
To start this lab I jumped into research as I had no experience with Palo Alto products prior to this. After gaining a good understanding of the process of how to factory reset this device I connected my pc to the firewall with a console cable and plugged in a power cable into the firewall to then boot it. As it was booting it prompted to enter maintenance mode by using the command “maint” which I did. After letting it load into maintenance mode I selected the factory reset option and the factory reset process began. I then let the factory reset process load until it was finished, once it was finished it prompted me asking if I wanted to reboot with the factory reset configuration which I did. Once it booted up, the factory reset process was complete and I was ready to move on to new labs with a clean configuration on the Palo Alto Firewall.
<br />

<h2>Lab Commands</h2>
-maint – boots the palo alto system into maintenance mode to begin the factory reset process.
<br />

<h2>Network Diagram</h2>
<p align="center">
  <img src="https://i.imgur.com/JG4RBcT.png" height="30%" width="30%" alt="Disk Sanitization Steps"/>
</p>
<br />

<h2>Walk-Through:</h2>

<p align="center">
On boot use maint command to enter maintanence mode when prompted<br/>
<img src="https://i.imgur.com/g8H867f.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
Once in maintanence mode select factory reset and enter to confirm<br/>
<img src="https://i.imgur.com/LCO9zVH.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
Wait for factory reset to complete<br/>
<img src="https://i.imgur.com/CxOLYm9.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
Once the factory reset is complete with a successful status, reboot<br/>
<img src="https://i.imgur.com/t8Ha1we.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
Now it boots in the default environment <br/>
<img src="https://i.imgur.com/3cat6dH.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
</p>

<h2>Conclusion</h2>
In this lab I factory reset a Palo Alto 220 Firewall after conducting research to find information on how to do so seeing as I had no prior knowledge on how to perform the objective. I had very little issues completing this lab as it’s main purpose was to simply set up for future labs. It also got me comfortable with using the Palo Alto’s console which I used to initiate the factory reset process. After this lab was completed the firewall was wiped of prior configuration and ready for me to start my own configuration.
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
