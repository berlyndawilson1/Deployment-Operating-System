# Operating-System-Deployment


<h2>Description</h2>
This project aims to illustrate the troubleshooting process for installation media during the operating system import procedure. The identified issue pertains to the media creation tool being classified as an electronic software, while the MDT deployment program exclusively recognizes WIM files. The outlined procedure will elucidate the steps involved in copying the ESD file to a separate directory and subsequently extracting a .wim file from it.
<br />

<h2>Troubleshooting Reference Used</h2>
- (https://community.spiceworks.com/t/convert-esd-to-wim/1012918/11)


<h2>Utilities Used</h2>

- <b>Deployment Workbench</b> 

<h2>Environments Used </h2>

- <b>Windows Server 2019</b>

<h2>Program walk-through:</h2>

<p align="center">
Download Windows 10 image: <br/>
<img src="https://imgur.com/Zxjv9er.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Select the OS:  <br/>
<img src="https://imgur.com/FQXR3Z3.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Selecting File Location: <br/>
<img src="https://imgur.com/yWC4uWj.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Error From Source Directory:  <br/>
<img src="https://imgur.com/QgTFqib.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Issue with ESD File:  <br/>
<img src="https://imgur.com/OKKvG5a.png" height="80%" width="80%" alt="OS Depolyment Steps"/>
<br />
<br />
ESD File Version Information  <br/>
<img src="https://imgur.com/dUkYKI0.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Exporting Completed:  <br/>
<img src="https://imgur.com/COtcSOY.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Select Custom Image File:  <br/>
<img src="https://imgur.com/BJaKXpl.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Source File WIM:  <br/>
<img src="https://imgur.com/GVA5Bfh.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Setup:  <br/>
<img src="https://imgur.com/oJ33Mi1.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Windows 10 Destination:  <br/>
<img src="https://imgur.com/tGEQhNn.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Windows 10 Destination:  <br/>
<img src="https://imgur.com/tGEQhNn.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Summary of Installation:  <br/>
<img src="https://imgur.com/9m0g2Hv.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Summary of Installation:  <br/>
<img src="https://imgur.com/9m0g2Hv.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Import Operation:  <br/>
<img src="https://imgur.com/US9OyS7.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Process Complete:  <br/>
<img src="https://imgur.com/4G0f2so.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
<br />
Operating System:  <br/>
<img src="https://imgur.com/R2ylmCB.png" height="80%" width="80%" alt="OS Deployment Steps"/>
<br />
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
