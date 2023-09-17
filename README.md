![image](https://github.com/davidclin/custom-pc-build/assets/6853545/0355e8b2-2ef4-4cb4-9fad-f4348b779153)

# Checklist
* Tower case
* Motherboard
* CPU
* Memory
* SSD Drive
* Cooling fan
* Power supply

# Tools
* Thermal paste
* Spreader
* Screwdriver
* Anti-static wristband
* Suction cup

# PC custom part site
To research and find parts compatibility and cost, check out [PC Part Picker](https://pcpartpicker.com/)
# Amazon Parts List
[See parts](https://a.co/6VKQqZ7)

# Create Windows 11 Installation Media (5 minutes)
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

# Purchase Windows 11 license 
[Purchase]()

# Install Windows 11
[Watch](https://youtu.be/RYYoCXh2gtw?si=Ab5xFY4sXr3_i93H
[Watch new](https://youtu.be/xhHtHMQygzE?si=5ye6W42zdQaH7qgc)
Tips:<br>
Connect without Internet<br>
Choose to instal with minimal setup<br>

# Update Windows
Perform all Windows updates before updating drivers

# Install manufacturer drivers
GPU (Best pratice to do clean install)
Motherboard (network, wifi, soundcard, ...)
etc

# Set BIOS to use full potentential of memory
[]()

# Download software that manages LEDs
[]() 

# Update BIOS
[]()

# How to install a liquid cooling fan
[Watch]()

# Tips & Tricks
* Use power cables provided by power supply to avoid accidentally frying your components
* Read the motherboard manual to understand which slots memory should be paired
* Look for arrows on air cooling unti to see direction of airflow
* Test everything before mounting the motherboard to the case
* Download wifi and network drivers beforehand as many motherboards do t have the drivers installed
