<h1>Assessment, Analysis, & Hardening Of A Vulnerable System</h1>

<h2>Description</h2>
This walkthrough shows the process of what a red an blue team does. The red team completes security assessments and reports their findings. The blue team takes the information from the red team and hardens vulnerable systems.
<br />


<h2>Resources Used</h2>

- <b>Virtual Machine (VM)</b> 
- <b>Resource Group</b>
- <b>Log Analytics Workspace</b>
- <b>Microsoft Defender for Cloud</b>
- <b>Azure Sentinel (Siem)</b>

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2) (VM)
- <b>Microsoft Azure</b> 

<h2>Walk-through:</h2>
<h2>Red Team:</h2>
<br>
<p align="center">
Network topology:<br/>
<a href="https://imgur.com/bScCZjs"><img src="https://i.imgur.com/bScCZjs.png" title="Network Topology" /></a>
Network Scan results with Nmap:<br/>
<a href="https://imgur.com/p0rSoa1"><img src="https://i.imgur.com/p0rSoa1.png" title="Nmap Scan Results" /></a>
Vulnerabilities found from Nmap scan:<br/>
<a href="https://imgur.com/ky4Th0o"><img src="https://i.imgur.com/ky4Th0o.png" title="Open Ports" /></a>
Port 22 Exploitation:<br/>
<a href="https://imgur.com/GsRZHt7"><img src="https://i.imgur.com/GsRZHt7.png" title="Port Exploitation" /></a>
Crackable Password Exploitation:<br/>
<a href="https://imgur.com/gCj9om9"><img src="https://i.imgur.com/gCj9om9.png" title="Brute Force Attack" /></a>
Reverse Shell Exploitation:<br/>
<a href="https://imgur.com/GGV2WfO"><img src="https://i.imgur.com/GGV2WfO.png" title="Reverse Shell" /></a>
<br>
<h2>Blue Team:</h2>
<br>
<p align="center">
Port Scan Data:<br/>
<a href="https://imgur.com/AW9wavU"><img src="https://i.imgur.com/AW9wavU.png" title="Port Scan Data" /></a>
Hidden Directory Request:<br/>
<a href="https://imgur.com/HdngbV9"><img src="https://i.imgur.com/HdngbV9.png" title="Hidden Directory Data" /></a>  
Brute force attack data:<br/>
<a href="https://imgur.com/8g2Z7Ne"><img src="https://i.imgur.com/8g2Z7Ne.png" title="Brute Force Attack" /></a>
<br>
<h2>Hardening The System</h2>
<br>
Blocking Port Scan:<br/>
<a href="https://imgur.com/tTuBBDD"><img src="https://i.imgur.com/tTuBBDD.png" title="Blocking Port Scan" /></a>
