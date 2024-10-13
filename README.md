<h1>Wazuh SIEM</h1>

<h2>Description</h2>
A comprehensive Security Information and Event Management (SIEM) lab set up in a home environment to practice and refine cybersecurity skills. This project simulates real-world network conditions and threats, enabling hands-on experience in log analysis, threat detection, and incident response. 
<br />

<h2>Project Hurdles and Outcome</h2>

<br />

<h2>Languages and Utilities Used</h2>

- <b>Wazuh (Open Source Security Platform</b> 
- <b>VMware</b>

<h2>Environments Used </h2>

- <b>Ubuntu Desktop 22.04.03 LTS VM</b>
- <b>Windows 11 (32H2)</b>

<h2>Program walk-through:</h2>

<p align="center">
Installing Wazuh on Ubuntu: <br/>
<img src="https://i.imgur.com/scTvqHc.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Temporary Credentials (web interface localhost port 443):  <br/>
 <img src="https://i.imgur.com/n9VWGLb.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wazuh Login: <br/>
<img src="https://i.imgur.com/sSTREYL.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Wazuh Dashboard: <br/>
<img src="https://i.imgur.com/PBUEPVV.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Deploy new Agent on Windows: <br/>
<img src="https://i.imgur.com/0VgXmWz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Running Command on Powershell as admin (Command:Invoke-WebRequest -Uri https://packages.wazuh.com/4.x/windows/wazuh-agent-4.9.0-1.msi -OutFile ${env.tmp}\wazuh-agent; msiexec.exe /i ${env.tmp}\wazuh-agent /q WAZUH_MANAGER='172.18.49.0' WAZUH_AGENT_NAME='windows' ): <br/>
<img src="https://i.imgur.com/zH1xfcz.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Start Wazuh on Windows: <br/>
<img src="https://i.imgur.com/THEW7r3.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Agent succesfully added: <br/>
<img src="https://i.imgur.com/oEDfaeQ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Different Events on the agent: <br/>
<img src="https://i.imgur.com/Y9mw36S.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Using Invoke AtomicRedTeam Framework for Demo: <br/>
<img src="https://i.imgur.com/EkDjueO.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Installing Invoke AtomicRedTeam: <br/>
<img src="https://i.imgur.com/bCa2D4f.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
MITRE ATT&CK Technique: <br/>
<img src="https://i.imgur.com/tjXKp7l.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generating Security Event on the Kali VM: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generating Security Event on the Kali VM: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Generating Security Event on the Kali VM: <br/>
<img src="" height="80%" width="80%" alt="Disk Sanitization Steps"/>
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
