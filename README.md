![image](https://github.com/davidclin/custom-pc-build/assets/6853545/0355e8b2-2ef4-4cb4-9fad-f4348b779153)

# Components
* Mid Tower case
* Motherboard
* CPU
* Memory
* SSD Drive
* Cooling fans
* Liquid CPU cooler
* Power supply 

# Tools
* Thermal paste
* Spreader
* Screwdriver
* Anti-static wristband
* Suction cup

# PC custom parts picker site
To research and find parts compatibility and cost, check out [PC Part Picker](https://pcpartpicker.com/)

# Parts List
Amazon | [Amazon](https://a.co/6VKQqZ7)<br>
Power Supply | [MWE Gold 850 v2 Full Modular](https://www.youtube.com/watch?v=YS73fJf62V4)<br>
Motherboard | [ROG Strix B550-F Gaming Wifi II](https://rog.asus.com/motherboards/rog-strix/rog-strix-b550-f-gaming-wifi-ii-model/helpdesk_bios/)<br>

# How to prepare and connect motherboard to NXT chassis
[Watch](https://www.youtube.com/watch?v=z51iV6ke3H0)

# How to install a power supply
[Watch](https://youtu.be/1AmR7enxnXI?si=nSY3HXPqcaSHQLyp)<br>

# Power supply cable types
<pre>
ATX 24 Pin  | for motherboard
EPS         | for CPU (easy to confuse with PCI-E)
PCI-E (6+2) | for GPU
SATA        | for SSD drive
Molex       | for older fans
</pre>

# Create Windows 11 Installation Media (5-8 minutes)
[Download](https://www.microsoft.com/en-us/software-download/windows11)<br>
Run as Administrator.<br>
If you're unable to format your USB using NTFS because it's too large:<br>
<pre>
Run cmd as Administrator
diskpart
list disk
select disk (disk #)
To get the disk # right click Start button and run Disk Management
attributes disk clear readonly
clean
create partition primary
format fs=ntfs quick
cntl+c (to break out)
chkdsk d: /f /r /x
Run Disk Management again to confirm USB is healthy
</pre>

# Purchase Windows 11 Pro license 
[Purchase](https://www.g2a.com/microsoft-windows-11-pro-pc-microsoft-key-global-i10000271164001)


# Install Windows 11
[Watch](https://youtu.be/RYYoCXh2gtw?si=Ab5xFY4sXr3_i93H
[Watch new](https://youtu.be/xhHtHMQygzE?si=5ye6W42zdQaH7qgc)
Tips:<br>
Connect without Internet<br>
Choose to instal with minimal setup<br>
<pre>
Shift + F10 to open prompt
oobe\bypassnro  
</pre>

# Update Windows
Perform all Windows updates before updating drivers

# Install manufacturer drivers
GPU (Best pratice to do clean install)<br>
  - update refresh rate<br>
Motherboard (network, wifi, soundcard, ...)<br>
etc<br>

# Flash BIOS
<pre>
S U M M A R Y
</pre>
* Format USB using FAT32
* Download latest BIOS firmware from manufacturer website
* Unzip then copy files to USB
* Rename file using provided renaming tool
* Insert USB into Flash BIOS USB port
* Hold Flash BIOS button down for 3 seconds
* Wait for BIOS update to complete
* DO NOT POWER OFF THE PC or REMOVE USB
* Remove USB once light stops flashing

<pre>
V I D E O 
</pre>
* [Watch](https://youtu.be/BgTDzW3tjGg?si=jjBueWCTrWWXg47v)<br>

<pre>
F I L E
</pre>
* [Download](https://rog.asus.com/motherboards/rog-strix/rog-strix-b550-f-gaming-wifi-ii-model/helpdesk_bios/)


# Update BIOS
[Watch](https://youtu.be/xhHtHMQygzE?si=5ye6W42zdQaH7qgc)


# Set BIOS to use full potentential of memory
[]()

# Download software that manages LEDs
[]() 

# Enable XMP
Go to BIOS and enable<br>
Verify memory is running at max in Task Manager
# How to install a liquid cooling fan
[Watch]()

# Set monitor refresh rate
Change monitor refresh rate so it matches the max allowed

# Tips & Tricks
* Use power cables provided by power supply to avoid accidentally frying your components
* Read the motherboard manual to understand which slots memory should be paired
* Look for arrows on air cooling unti to see direction of airflow
* Test everything before mounting the motherboard to the case
* Download wifi and network drivers beforehand as many motherboards do not have the drivers pre-installed
* Remember to take full advantage of your monitor's refresh rate

# Terms
<pre>
ATX  ATX stands for Advanced Technology Extended, and it is the most common and standard motherboard 
     size for desktop computers.
  
NZXT NZXT is an American computer hardware manufacturer based in Los Angeles, California. 
     The company manufactures computer cases, components, and accessories for the PC gaming market.
</pre>

# What is?
[M.2 NVMe SSD](https://youtu.be/HvfIeTieXOI?si=NUun_8WRvbHluK5G) <br>
[Motherboard]() <br>
Chipset <br>
Flash BIOS <br>
Headers  <br>

# YouTube
[How to build a PC - Step by Step](https://youtu.be/PXaLc9AYIcg?si=PTCYFdOd9vkp_Myc)<br>

