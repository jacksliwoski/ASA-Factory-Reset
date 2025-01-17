<h1>Cisco ASA Factory Reset</h1>


<h2>TLDR Description</h2>
Factory reset and Password Recovery on Cisco ASA 5505 Firewall
<br />

<h2>Purpose</h2>
The purpose of this lab was to familiarize myself with the basics of the ASA 5505 firewall by learning how and later implementing a factory reset and password recovery on the firewall to create a clean slate to begin my work on the firewalls.
<br />

<h2>Background Info</h2>
The ASA 5505 is a network firewall which was created in 2005, in its prime it was a pretty widely used firewall and still is used in a lot of places but it is nearing its end of life. This firewall focuses on its VPN functionality alongside its Intrusion Prevention and VoIP capabilities. 
<br />

<h2>Lab Summary</h2>
With a quick google search we were able to find the commands necessary to execute a password recovery and then do a factory reset on the ASA 5505. 
<br />

<h2>Lab Commands</h2>
  -  config factory-default – resets the asa to factory default.
  <br />
  -  copy startup-config running-config – loads startup config. 
<br />

<h2>Network Diagram</h2>
<p align="center">
  <img src="https://i.imgur.com/ze2lEBx.png" height="30%" width="30%" alt="Network Diagram"/>
</p>
<br />

<h2>Walk-Through:</h2>

<p align="center">
1<br/>
<img src="https://i.imgur.com/XRVO4Ow.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
2<br/>
<img src="https://i.imgur.com/Lk3iENN.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
3<br/>
<img src="https://i.imgur.com/cxzJ5Xr.png" height="80%" width="80%" alt="Palo Alto Firewall Factory Reset Steps"/>
<br />
<br />
</p>

<h2>Conclusion</h2>
This lab overall was pretty easy and was a very good way to ease myself into learning how to configure ASA firewalls, there is a ton of documentation regarding the 5505 as it was a pretty mainstream firewall so learning it is easier than some. With a quick google search I was pretty much able to find everything I needed to complete the lab and it turned out to be a lot simpler than I had initially thought when receiving the directions.
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
