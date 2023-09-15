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
To research and find parts compatibility and cost, check out <link goes here>

# Amazon Parts List
[See parts](https://a.co/6VKQqZ7)

# Create Windows 11 Installation Media
[Download](https://www.microsoft.com/en-us/software-download/windows11)<br>
Run as Administrator.<br>
If you're unable to format your USB because it's too large, try:<br>
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
</pre>

# Where to purchase Windows 11 license 
[Purchase]()

# How to install a liquid cooling fan
[Watch]()

# Tips & Tricks
