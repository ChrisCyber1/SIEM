<h1>SIEM Creation Home Lab</h1>


 
<h2>Description</h2>
In this project, I implemented a SIEM solution using Azure Sentinel. A virtual machine was created to collect security logs, and Sentinel was deployed and connected to a Log Analytics workspace. Windows security events were integrated, and a Data Collection Rule was configured. An alert rule was set up to detect successful logins from non-system accounts, and its functionality was validated through an RDP login test, confirming the system’s ability to monitor and respond to security events in real time.
<br />
<h2>Languages and Utilities Used</h2>

- <b>Azure Sentinel</b>

- <b>Log Analytics Workspace</b>

- <b>RDP (Remote Desktop Protocol)</b>

<h2>Environments Used </h2>

- <b>Windows Virtual Machine</b>

- <b>Microsoft Azure</b>

- <b>Azure Portal</b>

<h2>Project Walk-through:</h2>
<p align="center">
Created a Windows Virtual Machine (VM) in Microsoft Azure.: <br/>
<img src="https://i.gyazo.com/0f62b126fa9a72a1984fcc1fd4648120.png" height="80%" width="80%" alt="Setting up VirtualBox"/>
<br />
<br />
Deployed Azure Sentinel and connected it to a Log Analytics workspace:  <br/>
<img src="https://i.gyazo.com/2e09e33b36f30346af44f40a3ec0bc52.png" height="80%" width="80%" alt="Configuring Domain Controller"/>
<br />
<br />
Configured Windows Security Events to integrate with the Log Analytics workspace:  <br/>
<img src="https://i.gyazo.com/18faba65b6a8c0a8c98f1dfa85dc0f1b.png" height="80%" width="80%" alt="PowerShell User Creation"/>
<br />
<br />
Set up a Data Collection Rule to collect specific security events from the VM:  <br/>
<img src="https://i.gyazo.com/edfeebb057a0ca75ddce1238643e2034.png" height="80%" width="80%" alt="Windows 10 Domain Join"/>
<br />
<br />
Created an alert rule in Sentinel to detect successful logins from non-system accounts.:  <br/>
<img src="https://i.gyazo.com/3c7b0cae47b21a41e96a79ff1ef7b53c.png" height="80%" width="80%" alt="Testing Domain Functionalities"/>
<br />
<br />
Validated the setup by logging into the VM via RDP with a non-system account, triggering the alert rule.:  <br/>
<img src="https://i.gyazo.com/e61d26cca0cd3a7ba459ae3ad19a2d20.png" height="80%" width="80%" alt="Testing Domain Functionalities"/>
</p>
