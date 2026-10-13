<h1>1. Lab overview and Prerequisites</h1>
<p>This lab involves the setup of a Windows 10 Client and Windows Server 2022 in a virtual machine environment. Once they are installed I created a Domain Controller to house the Active Directory and assign 2 network adapters. One adapter is used to connect to the internet and the other is to connect to the virtualbox private network.</p>
<p>Before getting started here are some basic prerequisites for the setup both hardware and software</p>
<ul>
  <li>VirtualBox</li>
  <li>Windows Server 2022 VM</li>
  <li>Windows Client VM</li>
  <li>Sufficient RAM 16GB(Recommended), CPU 6 Cores(Recommended), Approximately 30GB of storage for the lab</li>
  <li>Purpose of Lab: Domain Authentication, Network Services and Windows Administration</li>
</ul>
<img src="https://github.com/user-attachments/assets/961e4ff6-44bf-41ad-9188-f24bce246539" style="max-width: 100%; height: auto;" alt="Network Diagram">
<br>
<h1>2. Virtual Machines and Network Configuration</h1>
<h2>Server and Client Virtual Machine Configurations</h2>
<p>Inside the VirtualBox virtual machine select "New", name the virtual machine DC for Domain Controller. Set the operating system as "Other Windows 64-bit".</p>
<p>Back to the VM main window in settings enable expert in the top left corner. Ensure both Shared Clipboard and Drag-and-Drop have bidirectional enabled in the dropdown. Go to the network tab and enable network adapter 2 and set it as "internal network"</p> 
<p>Once finished start up the DC virtual machine and select the Windows Server 2022.iso</p>
<img src="https://github.com/user-attachments/assets/60e1016b-1ee9-44a0-b43c-15d442319bb7" style="max-width: 100%; height: auto;" alt="Server Select">
<p>In the install menu select the "Desktop Experience" option and install to disk 0. <strong>While installing do not press anything</strong> and let it boot into windows. Once your in set a password</p>
<br>
<h3>Internal Network Interface Card (NIC) Setup</h3>
<ul>
  <li>Click on your network icon on the bottom right status bar > Unidentified Network > Change adapter options</li>
  <li>Once inside the window with 2 ethernet options check the IPv4 Address to identify if it's the home address i.e 10.x.x.xx. If its accurate then it would be the external NIC that is connected to the internet</li>
  <li>Automatically assigned ip of 169.x.x.xx would be the internal NIC</li>
  <li>Name both appropriately i.e INTERNET & X_INTERNAL_X</li>
</ul>
