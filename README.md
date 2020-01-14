# melodic-configure
Everything you need to configure a laptop with ROS Melodic and communicate with ROBOTIS turtlebot 3. 
Created for Stanford's AA274. 

Gen 1 laptops: 
2019 Lenovo Thinkpad E590 https://www.amazon.com/dp/B07W8THGC6/ref=cm_sw_em_r_mt_dp_U_hwwhEbPZZXTE3

- Windows 10 is installed using UEFI without a separate bootloader, so dual boot with Windows was tricky without re-installing Windows 10. Todo: keys are available, so this is still doable. 

- Ubuntu 18 isn't compatible with Secure boot on this BIOS: Go into Advanced BIOS settings (F12). 
Under Security, Change:
Secure Boot to [Disabled].

Under Startup>Boot>UEFI/Legacy Boot, set the option to be:
UEFI/Legacy Boot to [Both]
UEFI/Legacy Boot Priority to [UEFI First]
CSM Support to [YES]. 

Ubuntu 18 was installed with a separate UEFI disk (/dev/nvme0n1p1).



