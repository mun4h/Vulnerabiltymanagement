<h1>Vulnerability management</h1>


<h2>Description</h2>
This Project shows a simple demonstration of how to perform Vulnerability Scanning of a  Windows 10 machine virtual machine using a Scanner called Nessus Essentials.
<br />

<h2>Environments Used </h2>

- <b>Windows 10</b> (21H2)

- <b>Nessus Essentials</b>

<h2>Program walk-through:</h2>

- <b>Download and Install Nessus Essentials</b> 

- <b>Set a Virtual Machine</b>
<br />
<p align="center">
<b>Downloading and Installing Nessus Essentials</b>  </p>
Nessus Essentials can be downloaded from <a href="https://www.tenable.com/products/nessus/nessus-essentials">here</a> 
<br />
Register by putting your First Name, Last Name, and Email address then click "Get Started"
<br />
On the next page, you will get confirmation that the activation code has been sent to the email address used to register and click "Download"
<br />

<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/Inked10.jpg" height="80%" width="80%"/> 
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/11.png" height="80%" width="80%"/>

<br />
Select Windows File, agree to the agreement, and Install the application
<br/>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/11a.png" height="50%" width="80%"/>
<br />
<br/>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/12.png" height="50%" width="80%"/>
<br />
<br/>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/15.png" height="50%" width="80%"/>
<br/>
<br/>
Double-click the installed application and it will open in a browser and click on the "connect via SSL"
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/16.png" height="50%" width="80%"/>
<br />
<br />
On the next page, select "Advanced" and hit "Continue to localhost(unsafe)"
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/17.png" height="30%" width="100%"/>
<br />
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/18.png" height="30%" width="100%"/>
Sign up on the next page and sign in to the Nessus console
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/19.png" height="30%" width="100%"/>
<br />
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/Inked32.jpg" height="100%" width="100%"/>
<br />
<br />
<p align="center">
Set a Virtual Machine  </p>
</p>
I will be using VMware Workstation Player to host the Virtual Machine 
<br>
<br>VMware can be downloaded <a href="https://www.vmware.com/ca/products/workstation-player.html">here</a> and Windows 10 download tool can be downloaded from <a href="https://www.microsoft.com/en-ca/software-download/windows10">here</a>
<br />
<br>Download the Workstation Player<br />
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/1.png" height="30%" width="100%"/> 

<br>Download the Windows 10 download tool<br />
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/2.png" height="30%" width="100%"/> 
<br>Open the tool to create the ISO file<br />
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/3.png" height="30%" width="100%"/>
<br>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/4.png" height="30%" width="100%"/>
<br>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/5.png" height="30%" width="100%"/> 
<br>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/6.png" height="30%" width="100%"/> 
<br>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/7.png" height="30%" width="100%"/> 
<br>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/8.png" height="30%" width="100%"/> 
<br>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/9.png" height="30%" width="100%"/> <br />

<br>Open the installed VMWare Player Workstation, add the downloaded ISO, and Install Windows 10 OS <br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/20.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/21.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/22.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/23.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/24.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/25.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/26.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/27.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/28.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/29.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/30.png" height="30%" width="100%"/> 
<br />
<p align="center">
Scanning the Virtual Machine for any Vulnerability  </p>
</p>
<br>First I need to get the IP address of the Virtual Machine<br />
<br>
<img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/31.png" height="30%" width="100%"/>
<br />

<br>Ping the VM <br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/33.png" height="30%" width="100%"/> 
<br />
<br>If the Ping isn't successful, search for Windows Defender Firewall with Advanced Security and turn off the Domain, Private & Public profiles to fix the issue <br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/34.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/35.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/35a.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/36.png" height="30%" width="100%"/> 
<br />
<br>Open Nessus Essential and create a new Scan<br />
<br>There are 2 types of Scan that can be set up<br />
- <b>Credentialess Scan</b>
- <b>Credentialed Scan- Which generates more results </b> 
<br><br/>
<p align="center">
For Credentialess Scan  </p>
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/32.png" height="30%" width="100%"/> 
<br />
<br>Go to Basic Network Scan to start set up and start the Scan<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/37.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/38.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/39.png" height="30%" width="100%"/> 
<br />
<br>Once the scan is done, click on the VM name to view the log result<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/40.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/41.png" height="30%" width="100%"/> 
<br />
<br>Go to Vulnerabilities and any of the vulnerabilities listed<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/42.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/43.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/44.png" height="30%" width="100%"/> 
<br />
<br>Implement the solution to remediate the Vulnerability<br />
<br><br/>
<p align="center">
For Credentialed Scan  </p>
<br>Go to the VM, then go to the Services on it and enable ad start Remote registry which will allow the scanner to the VM's registry<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/46.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/47.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/48.png" height="30%" width="100%"/> 
<br />
<br>Make sure Network and Print sharing are both turned on <br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/49.png" height="30%" width="100%"/> 
<br />
<br>Disable the User account control settings<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/50.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/50a.png" height="30%" width="100%"/> 
<br />
<br>Next is to go to Registry Editor and add a key that further disables user account control for the remote account that is to connect to the VM for the Scan as per Nessus recommendation<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/51.png" height="30%" width="100%"/> 
<br />
<br>Add a new DWORD(32-bit) called "LocalAccountTokenFilterPolicy" in this location: Computer\HKEY_LOCAL_MACHINE\SOFTWARE\Microsoft\Windows\CurrentVersion\Policies\System<br />
<br>Set the Value to 1 and restart the VM<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/51a.png" height="30%" width="100%"/> 
<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/51b.png" height="30%" width="100%"/> 
<br />
<br>Next is to edit the already existing scan with credentials<br />
<br>Go to the VM's name then more and configure<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/45.png" height="30%" width="100%"/> 
<br />
<br>Configure the Scana nd add the VM's username and password<br />
<br><img src="https://github.com/mun4h/Vulnerabiltymanagement/blob/main/52.png" height="30%" width="100%"/> 
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
