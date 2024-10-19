<h1>SIEM Home Lab</h1>


<h2>Description</h2>
I established a home lab featuring Elastic SIEM alongside a Kali VM. I configured the Elastic Beats agent to forward data from the Kali VM to the SIEM. Utilizing Nmap, I generated security events on the Kali VM and then queried and analyzed the logs in the SIEM through the Elastic web interface. Additionally, I developed a dashboard to visualize security events and set up alerts to detect these events effectively.
<br />


<h2>Languages and Utilities Used</h2>

- <b>Bash</b> 

<h2>Environments Used </h2>

- <b>Elastic SIEM</b>
- <b>Virtual Box</b>
- <b>Kali VM</b>

<h2>Program walk-through:</h2>

<p align="center">
Setup Elastic Account: <br/>
<img src="https://i.imgur.com/K7h238x.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Download Kali VM:  <br/>
<img src="https://i.imgur.com/AP0w2ka.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Download Virtual Box: <br/>
<img src="https://i.imgur.com/bZwzmSP.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Add Kali VM to Virtual Box:  <br/>
<img src="https://i.imgur.com/K6Ez3NW.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Setup Defend Inetgration on Elastic and add to Kali VM:  <br/>
<img src="https://i.imgur.com/LCfeybq.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Check Status:  <br/>
<img src="https://i.imgur.com/R2UeFEu.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Run Nmap command:  <br/>
<img src="https://i.imgur.com/xZ24ifF.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Check logs on Elastic stack:  <br/>
<img src="https://i.imgur.com/ZTH550X.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Create Visualization:  <br/>
<img src="https://i.imgur.com/j27tKZl.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Create Rule:  <br/>
<img src="https://i.imgur.com/luykfwP.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
<br />
<br />
Create Email Alert:  <br/>
<img src="https://i.imgur.com/UEWJTDc.png" height="80%" width="80%" alt="SIEM Lab Steps"/>
</p>


