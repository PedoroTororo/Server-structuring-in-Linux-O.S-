<h1>Server structuring in Linux O.S</h1>

<h2>Description</h2>
This was one of the biggest projects I have ever done for my college in the two and a half years of my course. The project consists of the creation and initial configuration of a small virtual network for testing, using Debian 12 O.S (a Linux partition). The small network consisted of two virtual machines, one webserver and one gateway. At the time, it took me about four hours to complete this task, but due to my mistakes, I ended up having to start the work from scratch. That's why it took so long.
<br />


<h2>Utilities Used</h2>

- [<b>Oracle VirtualBox</b>](https://www.virtualbox.org)
- [<b>Debian 12</b>](https://www.debian.org/download)

<h2>O.S Used to host the VMs </h2>

- <b>Windows 10</b> 

<h2>Project walk-through:</h2>

<p align="center">
Installing the Utility: <br/>
<img src="https://i.imgur.com/PcXe4tg.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Launch the utility, when i create the first VM (Gateway): <br/>
<img src="https://i.imgur.com/d87FnS8.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Set the requeriments:  <br/>
<img src="https://i.imgur.com/jBvk1KJ.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<img src="https://i.imgur.com/2wIF9au.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After creating the VM, its access ports were configured. For obvious reasons, I will not show a screenshot of this here. So we continued with the installation of the OS on the VM: <br/>
<img src="https://i.imgur.com/Wj9wWhW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
After that, it is necessary to configure the machine. Again, I will not explain this here for reasons of confidentiality. After the OS is installed and configured, the same process is repeated from scratch, after, all will looks like this: <br/>
<img src="https://i.imgur.com/b56visW.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />
Well, after that, there are several lines of code to set the IP address on each machine and let them communicate. If everything is correct, when you type the IP address that was set on the VMs into a browser, the following page should appear. If nothing loads, there is an error in your project: <br/>
<img src="https://i.imgur.com/LJuKZrA.png" height="80%" width="80%" alt="Disk Sanitization Steps"/>
<br />
<br />


<h1>Conclusion</h1>

Although it was time-consuming and repetitive, the process of redoing this work twice in the same day helped me build muscle memory for the codes needed to configure the VMs in Debian 12 CMD. It was difficult, but with effort and dedication, I was able to complete this project.
