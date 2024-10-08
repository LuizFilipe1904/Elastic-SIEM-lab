<h1>Elastic SIEM Lab</h1>

<h2>Description</h2>
Settiing up a home lab for Elastic Stack Security Information and Event Management (SIEM) using the Elastic Web portal and Kali Linux VM. Generating security events on the kali VM, setting up an agent to forward data to the SIEM, and query analyzing the logs in the SIEM.
<br />


<h2>Systems and Utilities Used</h2>

- <b>Kali Linux</b>
- <b>Elastic SIEM</b>

<h2>Setup walk-through:</h2>

<p align="center">
Elastic Deployment Created: <br/>
<img src="https://i.imgur.com/JgHCHKw.png" height="80%" width="80%" alt="Elastic Deployment Created"/>
<br />
<br />
Setting up the agent to collect logs from Kali VM and forward them to Elastic SIEM instance:  <br/>
<img src="https://i.imgur.com/LZuGAX0.png" height="80%" width="80%" alt="Search Elastic Defend"/>
<img src="https://i.imgur.com/8BnM87d.png" height="80%" width="80%" alt="Add Elastic Defend"/>
<img src="https://i.imgur.com/QbADYzk.png" height="80%" width="80%" alt="Add Agent Kali"/>    
<br />
<br />
Using Nmap to verify if the agent is working correctly: <br/>
<img src="https://i.imgur.com/fUhW9s3.png" height="80%" width="80%" alt="Nmap"/>
<img src="https://i.imgur.com/uxGkhcm.png" height="80%" width="80%" alt="Nmap"/>  
<img src="https://i.imgur.com/otk3Cl4.png" height="80%" width="80%" alt="Nmap"/>    
<br />
<br />
Querying for Security Events in the Elastic SIEM:  <br/>
<img src="https://i.imgur.com/QFFofKg.png" height="80%" width="80%" alt="Query"/>
<br />
<br />
Creating a Dashboard to visualize the events:  <br/>
<img src="https://i.imgur.com/6uoLeyC.png" height="80%" width="80%" alt="Dashboard"/>
<img src="https://i.imgur.com/j9bvuFZ.png" height="80%" width="80%" alt="Dashboard"/>
<img src="https://i.imgur.com/MffAz0J.png" height="80%" width="80%" alt="Dashboard"/>
<img src="https://i.imgur.com/n2Bajdj.png" height="80%" width="80%" alt="Dashboard"/>  
<br />
<br />
Creating an alert to detect Nmap scans:  <br/>
<img src="https://i.imgur.com/Gy1esMM.png" height="80%" width="80%" alt="Alert"/>
<img src="https://i.imgur.com/32zgrfP.png" height="80%" width="80%" alt="Alert"/>
<img src="https://i.imgur.com/392qVdG.png" height="80%" width="80%" alt="Alert"/>
<img src="https://i.imgur.com/izjZ2Gt.png" height="80%" width="80%" alt="Alert"/>
<img src="https://i.imgur.com/fp1pQdN.png" height="80%" width="80%" alt="Alert"/>
<img src="https://i.imgur.com/L6uN7Lq.png" height="80%" width="80%" alt="Alert"/>
<br />
<br />


