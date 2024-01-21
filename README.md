<h1>Home Network Lab</h1>


<h2>Description</h2>
Project consists of a simple PowerShell script that walks the user through "zeroing out" (wiping) any drives that are connected to the system. The utility allows you to select the target disk and choose the number of passes that are performed. The PowerShell script will configure a diskpart script file based on the user's selections and then launch Diskpart to perform the disk sanitization.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Packet Tracer</b> 

<h2>Environments Used </h2>

- <b>Windows 11</b>

<h2>Program walk-through:</h2>

<p align="center">
End devices: Laptops, Pc, printer, server, smartphone and tablet <br/>
<img src="https://i.imgur.com/pEmvob5.png" height="80%" width="80%"/>
<br />
<br />
<br />
Wired connection made between router and pc:  <br/>
<img src="https://i.imgur.com/NyexsSp.png" height="80%" width="80%"/>
<br />
<br />
<br />
Enabling DHCP to receive network gateway address: <br/>
<img src="https://i.imgur.com/4dZi70d.png" height="80%" width="80%"/>
<br />
<br />
<br />
loging in with default username 'admin' and password 'admin':  <br/>
<img src="https://i.imgur.com/6H1Uie9.png" height="80%" width="80%"/>
<br />
<br />
<br />
Configuring the router:  <br/>
<img src="https://i.imgur.com/2tACndW.png" height="80%" width="80%"/>
<br />
<br />
<br />
Set network SSID to 'Home WiFi' from 'Default':  <br/>
<img src="https://i.imgur.com/m7ZyxLW.png" height="80%" width="80%"/>
<br />
<br />
<br />
Set security protocol/mode to 'WPA2 Personal' from 'Disabled':  <br/>
<img src="https://i.imgur.com/hVN68B7.png" height="80%" width="80%"/>
<br />
<br />
<br />
Set nwetwork passphrase to 'WifiPassword': <br />
<img src="https://i.imgur.com/OYAmToy.png" height="80%" width="80%"/>
<br />
<br />
<br />
Change Router Login password from 'admin' to 'Password': <br />
<img src="https://i.imgur.com/MKO2xV3.png" height="80%" width="80%"/>
<br />
<br />
<br />
Search for 'Home WiFi' on wireless end devices <br />
<img src="https://imgur.com/Ro96RK6.png" height="80%" width="80%"/>
<br />
<br />
<br />
Connect wireless end devices to 'Home WiFi' using the passphrase 'WifiPassword'
<img src="https://i.imgur.com/QInhvKm.png" height="80%" width="80%"/>
<br />
<br />
<br />
All wireless end devices connected: <br />
<img src="https://i.imgur.com/bLeukCb.png" height="80%" width="80%"/>
<br />
<br />
<br />
Configuring server <br />
<img src="https://i.imgur.com/jCIlgTh.png" height="80%" width="80%"/>
<br />
<br />
<br />
Taking note of the server's display name and MAC address <br />
<img src="https://i.imgur.com/PaW7yHx.png" height="80%" width="80%"/> 
<br />
<br />
<br />
Reserving a DHCP for 'Server0' on the router <br />
<img src="https://i.imgur.com/swEMCJU.png" height="80%" width="80%"/>
<br />
<br />
<br />
DHCP successfully reserved for 'Server0' <br />
<img src="https://i.imgur.com/wWExTbs.png" height="80%" width="80%"/>
<br />
<br />
<br />
Pinging 'Server0' <br />
<img src="https://i.imgur.com/hFRHQ9n.png" height="80%" width="80%"/>
<br />
<br />
<br />
Configuring printer: <br />
<img src="https://i.imgur.com/Ud19PpM.png" height="80%" width="80%"/>
<br />
<br />
<br />
Taking note of the printer's display name and MAC address: <br />
<img src="https://i.imgur.com/44TSLcQ.png" height="80%" width="80%"/>
<img src="https://i.imgur.com/bDy1TFH.png" height="80%" width="80%"/>
<br />
<br />
<br />
Reserving a DHCP for 'Printer0'
<img src="https://i.imgur.com/IqEZ5yG.png" height="80%" width="80%"/>
<br />
<br />
<br />
'Printer0' successfully reserved
<img src="https://i.imgur.com/47QHsYm.png" height="80%" width="80%"/>
<br />
<br />
<br />
<img src="https://i.imgur.com/bDy1TFH.png" height="80%" width="80%"/>
<br />
<br />
<br />
</p>

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
