# Casa-OS-with-Raspberry-Pi

![alt text](https://hackster.imgix.net/uploads/attachments/1587811/3_eXtHaT6IhA.png?auto=compress%2Cformat&w=740&h=555&fit=max)

Casa OS is a simple, easy-to-use, elegant open-source home cloud system that allows you to run self-hosted apps on your Raspberry Pi or other Linux devices. You can manage your files, share them across the network, protect your privacy data, and freely add disks and expansion spaces. Casa OS also has an app store with over 20 pre-installed docker based apps and 50+ community-verified apps. CasaOS fully supports Raspberry Pi. Also, more computers and development boards and fully compatible with Ubuntu, Debian, Raspberry Pi OS, and CentOS with one-liner installation.
CasaOS fully supports ZimaBoard, Intel NUC, and Raspberry Pi. Also, more computers and development boards and fully compatible with Ubuntu, Debian, Raspberry Pi OS, and CentOS with one-liner installation.

![alt text](https://hackster.imgix.net/uploads/attachments/1587814/image_FR7raNjA5e.png?auto=compress%2Cformat&w=740&h=555&fit=max)

Raspberry Pi is a series of small single-board computers (SBCs) developed in the United Kingdom by the Raspberry Pi Foundation in association with Broadcom. The Raspberry Pi project originally leaned towards the promotion of teaching basic computer science in schools.The original model became more popular than anticipated, selling outside its target market for uses such as robotics. It is widely used in many areas, such as for weather monitoring,[19] because of its low cost, modularity, and open design. It is typically used by computer and electronic hobbyists, due to its adoption of the HDMI and USB standards.

The Raspberry Pi 4 Model B was released in June 2019 with a 1.5 GHz 64-bit quad core ARM Cortex-A72 processor, on-board 802.11ac Wi-Fi, Bluetooth 5, full gigabit Ethernet (throughput not limited), two USB 2.0 ports, two USB 3.0 ports, 1–8 GB of RAM, and dual-monitor support via a pair of micro HDMI (HDMI Type D) ports for up to 4K resolution. The version with 1 GB RAM has been abandoned and the prices of the 2 GB version have been reduced. The 8 GB version has a revised circuit board. The Pi 4 is also powered via a USB-C port, enabling additional power to be provided to downstream peripherals, when used with an appropriate PSU.

![alt text](https://hackster.imgix.net/uploads/attachments/1587815/6_VR7FOXNc1N.png?auto=compress%2Cformat&w=740&h=555&fit=max)

Now we have enough information about the Casa, let's try to install it. Before installing the casa, first boot your Raspberry pi with Raspian OS. Use the Raspberry Pi imager tool to do that. Once installed, the software opens the tool. Next, choose the OS type.Then select the drive. One of the great features of this tool is we can add the SSH and Wi-Fi credentials directly into the OS file, even without turning on the Raspberry Pi. For that, select the settings icon in the tool.Next, start burning the OS into the SD card.Once the writing is finished, insert the SD card into the Raspberry Pi.

Then power on the device. The first time it will take some to boot and connect to Wi-Fi to 5–10 minutes and look at your router status, you can see there will be a new device connected to your router. Next, use serial terminal software to communicate with SSH.Then run this command to install the casaos.

curl -fsSL https://get.casaos.io | sudo bash

You will see this message on the terminal, first it will try to install all the necessary components regarding the casa os.Once the installation is finished, you will see this kind of message also an IP address of the casa server.Next type the Ip in the Brower, you will see the casa os screen.And then click the Go and enter your access details for the casa os.Finally, you will see the beautifull home screen. Next click on the app store, you can see threre are bunch of pre available apps.Also open the file manager, you will see all the files of your raspberry,not only the system drive. It will show you the removable drive also.


![alt text](https://hackster.imgix.net/uploads/attachments/1544797/pcbway_55Vl7NMRFG.JPG?auto=compress%2Cformat&w=740&h=555&fit=max)

You must check out [PCBWAY](https://www.pcbway.com/) for ordering PCBs online for cheap!

You get 10 good-quality PCBs manufactured and shipped to your doorstep for cheap. You will also get a discount on shipping on your first order. Upload your Gerber files onto PCBWAY to get them manufactured with good quality and quick turnaround time. [PCBWay](https://www.pcbway.com/) now could provide a complete product solution, from design to enclosure production. Check out their online Gerber viewer function. With reward points, you can get free stuff from their gift shop.
