<h1>VirtualBox - Active Directory Home Lab</h1>

<h2>Description</h2>
In this project setup an active directory to simulate technology that would be used in an production environment. I achieved
this by downloading Windows 10 Pro and Server 2019 iso’s and configured them as a client and
domain controller. I also setup the internal network by signing the IP address. After I created a
domain, configured NAT and routing to allow client access. Then I setup a DHCP to allow the
client to get an IP address that allows access to internet while remaining on the private internal
network. Finally, I ran a PowerShell script that created and added 1000+ users into the active directory. I ended this lab by testing the login and accessing the internet from the client's end.
<br/>


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>VirtualBox</b>

<h2>Environments Used </h2>

- <b>Windows 10 Pro</b>
- <b>Microsoft Server 2019</b>
- <b>VirtualBox</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch the utility: <br/>
<img src=""/>
<br />
<br />
Select the disk:  <br/>
<img src=""/>
<br />
<br />
Enter the number of passes: <br/>
<img src=""/>
<br />
<br />
Confirm your selection:  <br/>
<img src=""/>
<br />
<br />
Wait for process to complete (may take some time):  <br/>
<img src=""/>
<br />
<br />
Sanitization complete:  <br/>
<img src=""/>
<br />
<br />
Observe the wiped disk:  <br/>
<img src=""/>
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
