<h1>VirtualBox - Active Directory Home Lab</h1>

<h2>Description</h2>
Built a virtualized Windows enterprise environment using Windows Server 2022 and a Windows client to practice Active Directory administration, networking, Group Policy, PowerShell automation, and Windows troubleshooting.
<br/>

<h2>Environment</h2>
<table>
 <tr>
  <th>Component</th>
  <th>Configuration</th>
 </tr>
 <tr>
  <td>Hypervisor</td>
  <td>VirtualBox</td>
 </tr>
  <tr>
  <td>Server</td>
  <td>Windows Server 2022</td>
 </tr>
  <tr>
  <td>Client</td>
  <td>Windows 10/11</td>
 </tr>
  <tr>
  <td>Directory</td>
  <td>Active Directory Domain Services (ADDS)</td>
 </tr>
  <tr>
  <td>Networking</td>
  <td>DNS, DHCP, NAT, Internal Network</td>
 </tr>
  <tr>
  <td>Automation</td>
  <td>Powershell</td>
 </tr>
  <tr>
  <td>Management</td>
  <td>AD Users & Computers, Group Policy</td>
 </tr>
</table>

<h2>What I implemented</h2>
<ul>
 <li>Configured Windows Server 2022 as an Active Directory Domain Controller and established a Windows domain environment.</li>
 <li>Configured DNS, DHCP, NAT, and routing to provide network services and Internet connectivity to an isolated client network.</li>
 <li>Created and managed Active Directory users and administrative accounts, including automated creation of approximately 1,000 users using PowerShell.</li>
 <li>Joined a Windows client to the domain and verified network connectivity, authentication, and user access.</li>
 <li>Configured and tested Group Policy settings for centralized Windows security and workstation management.</li>
</ul>

<h2>Troubleshooting Examples</h2>
<p><strong>Domain Connectivity Issue</strong></p>
<p>The Windows client was unable to communicate with the Domain Controller. I investigated the server and network configuration, identified the underlying issue, restored the server/network service, and verified connectivity using Windows networking tools.</p>
<li>Troubleshooting Guide</li>
<br>
<p>Updates in progress, page will be reorganized and updated soon!</p>
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
