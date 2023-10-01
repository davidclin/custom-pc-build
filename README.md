<h1>MY PERSONAL PC BUILD | 2023</h1> 

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
* Magnetized screwdriver
* Anti-static wristband
* Suction cup
* Cable ties
* Magnetised screw tray
* Hemostat

# Screw types
* 6-32 x 5mm | used to mount motherboard
* 6-32 (hexagon) x 6mm | ?
* M3 x 5mm | used for
* KB5 x 10mm | used for
* Standoff 6-32 x 6.5 + 4mm Standoff wrench

# PC custom parts picker site
To research and find parts compatibility and cost, check out [PC Part Picker](https://pcpartpicker.com/)

# Parts List
Amazon       | [Amazon](https://a.co/6VKQqZ7)<br>
Power Supply | [MWE Gold 850 v2 Full Modular](https://www.youtube.com/watch?v=YS73fJf62V4)<br>
Motherboard | [ROG Strix B550-F Gaming Wifi II](https://rog.asus.com/motherboards/rog-strix/rog-strix-b550-f-gaming-wifi-ii-model/helpdesk_bios/)<br>
...

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

# How to jump a motherboard without a power button
Use a screwdriver or anything conductive to connect the pins on the motherboard used to power the pc on<br>
[Watch](https://www.youtube.com/watch?v=FuPZlliGqBw)<br>
![jumping-pc-power-on-pins](https://github.com/davidclin/custom-pc-build/assets/6853545/29f1e1e8-746d-49d1-847b-29f7081d33d3)


# How to create Windows 11 installation media (5-8 minutes)
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

# Purchasing Windows 11 Pro license 
[Purchase](https://www.g2a.com/microsoft-windows-11-pro-pc-microsoft-key-global-i10000271164001)


# Installing Windows 11
[Watch](https://youtu.be/RYYoCXh2gtw?si=Ab5xFY4sXr3_i93H
[Watch new](https://youtu.be/xhHtHMQygzE?si=5ye6W42zdQaH7qgc)
Tips:<br>
Connect without Internet<br>
Choose to install with minimal setup<br>
<pre>
Shift + F10 to open prompt
oobe\bypassnro  
</pre>
If Windows 11 installer doesn't boot from USB of the ROG Strix 550-F Gaming Wifi II motherboard, make sure USB is inserted in the Type C port (Red)!<br>
![IMG_4739](https://github.com/davidclin/custom-pc-build/assets/6853545/cee83e01-6a2d-477a-9132-0a98b6499e7a)

# Updating Windows
Perform all Windows updates before updating drivers

# Installing manufacturer drivers 
<pre>
For the ROG Strix 550-F Gaming Wifi II Motherboard
  - Software and Utility | Download from ASUS website
  - LAN | Windows 11 will automatically update
  - Wireless | Windows 11 will automatically update
  - Chipset | Download latest AMD drivers from ASUS website 
  - Audio | Download latest Realtec drivers from ASUS website
  - VGA | Windows 11 will automatically update
  - Bluetooth | Download latest drivers from ASUS website
GPU 
  - Best pratice to do clean install
  - update refresh rate
</pre>

Screenshot of chipset driver installation<br>
![IMG_4751](https://github.com/davidclin/custom-pc-build/assets/6853545/ca769146-deba-4be0-bc66-d30b6fd0ad58)


# Enable XMP 
To get the max out of your memory, enable this feature in BIOS
- 
# Flash BIOS using BIOS Flashback
<pre>
Format USB | 3 minutes
</pre>
* Run cmd as Administrator
* diskpart
* list disk
* select disk (disk #)
* To get the disk # right click Start button and run Disk Management
* attributes disk clear readonly
* clean
* convert mbr  <---- SUPER IMPORTANT
* create partition primary
* format fs=fat32 quick
* cntl+c (to break out)
* chkdsk d: /f /r /x
* Run Disk Management again to confirm USB is healthy
    
<pre>
Flash the BIOS | 5 minutes
</pre>
* [Download](https://rog.asus.com/motherboards/rog-strix/rog-strix-b550-f-gaming-wifi-ii-model/helpdesk_bios/) latest BIOS firmware from manufacturer website
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
* Don't pull your fan off the CPU! [Watch](https://youtube.com/shorts/F0MZ8RflQWg?si=_u6hd6wEbUFWOlxz)
* To boot to UEFI from Windows 11, Shift + Restart -> Troubleshooting -> Advanced options -> UEFI Settings -> Restart
* Aim for neutral pressure. Avoid negative pressure (e.g. air outtake > air intake) as it can increase dust buildup inside your case.

# Troubleshooting
[Troubleshooting a PC with no POST or on display](https://www.youtube.com/watch?v=0wDUN1DqRrw)<br>
[Why there is no display when plugging HDMI without a dedicated GPU](https://www.quora.com/Can-a-Ryzen-5-5600X-run-without-a-GPU)<br>
If you're able to POST and enter BIOS but the power supply and GPU fans suddenly stop, make sure the heat sink is installed on the CPU to prevent overheating.<br>
The motherboard will try to protect the CPU if it gets too hot and it will quickly if there is no heat sink!<br>

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
UEFI <br>
Permeation <br>


# YouTube
[How to build a PC - Step by Step](https://youtu.be/PXaLc9AYIcg?si=PTCYFdOd9vkp_Myc)<br>
[How to kill your CPU cooler](https://youtu.be/BbGomv195sk?si=CoNhRNI2VXvY_YyG) <br>
