<h1> Windows Server (Hyper-V) </h1>


<h2>Description</h2>
DNS name resolution is a core service of the Internet and a business network. It is primarily used to resolve DNS names to IP addresses that are used to identify devices in an IP network. In this lab, I will explore the components and operation of the DNS service and protocol..
<br />


<h2>Languages and Utilities Used</h2>

- <b>Windows Server 2019</b>
- <b>PowerShell</b>
- <b>Hyper-V Manager</b>
- <b>WireShark</b>

<h2>Program Screenshots:</h2>

<p align="center">
Install DNS Role: <br/>
<img src="https://i.imgur.com/60CVa6H.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure the Preferred DNS Server address on the LAN network adapter :  <br/>
<img src="https://i.imgur.com/dmh5Vf9.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
NSLOOKUP command to verify that the DNS server is working AND Server command to set the default server to the IP address of Server-01: <br/>
<img src="https://i.imgur.com/lsPdOLN.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
NSLOOKUP to verify that the DNS client can query the address of Internet hosts AND Server command to set the default server to the IP address of Server-01: <br/>
<img src="https://i.imgur.com/YTUTLrn.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Configure network adapters for the Client-01 and Client-02 to use the Preferred DNS :  <br/>
<img src="https://i.imgur.com/xZoEiUh.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
View DNS :  <br/>
<img src="https://i.imgur.com/OQv8WN1.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Capture DNS packets (WireShark):  <br/>
<img src="https://i.imgur.com/qAtHQVk.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
