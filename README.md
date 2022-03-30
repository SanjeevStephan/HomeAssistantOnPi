# Getting Started with Home Assistant on Raspberry Pi (<a href="https://randomnerdtutorials.com/getting-started-with-home-assistant-on-raspberry-pi/" target="_blank">Full Guide</a>)
I’ll show you how to set up Home Assistant and to build a simple example to get you started with home automation

### What is Home Assistant?
<img src="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2017/09/home-assistant.png?resize=220%2C220&quality=100&strip=all&ssl=1" width="90px" height="90px">
<a href="https://www.home-assistant.io/" target="_blank">Home Assistant</a> is an home automation hub. An home automation hub is a place where <a href="https://www.home-assistant.io/integrations/" target="_blank">different devices</a> with different protocols communicate with each other. 
Home Assistant is the biggest open-source home automation platform to date and it supports 895 different components.

### Installing and Setting Up Home Assistant
To start running Home Assistant on the RPi, you need to install Hass.io.We recommend a dedicated system to run Home Assistant such as a <a href="">Raspberry Pi</a>.

#### SUGGESTED HARDWARE
We will need a few things to get started with installing Home Assistant.
* Raspberry Pi 4 (Raspberry Pi 3 is ok too, if you have one laying around)
* Power Supply for Raspberry Pi 4 or Power Supply for Raspberry Pi 3
* Micro SD Card. Ideally get one that is Application Class 2 as they handle small I/O much more consistently than cards not optimized to host applications. A 32 GB or bigger card is recommended.
* SD Card reader. This is already part of most laptops, but you can purchase a standalone USB adapter if you don’t have one. The brand doesn’t matter, just pick the cheapest.
* Ethernet cable. Required for installation. After installation, Home Assistant can work with Wi-Fi, but an Ethernet connection is more reliable and highly recommended.

#### DOWNLOAD HASS.IO OS & INSTALL

1) Go to https://www.home-assistant.io/installation/raspberrypi and chose the appropriate image for your Raspberry Pi. We recommend using Raspberry Pi 3. Click on the Raspberry Pi 3 link to download the Hass.io image to your computer.
2) Go to https://etcher.io/ and install Etcher on your computer.
3) When the installation is done, open Etcher and click on Select image you’ve just downloaded from <a href=" https://www.home-assistant.io/installation/raspberrypi">home-assistant.io</a>
4) Make sure Etcher selects the right SD card. Then, click Flash! Note: you need to have your SD card formatted before doing this step. Wait a few minutes while Etcher flashes the image on the SD card. <img src="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2017/09/flash-etcher.png?w=700&quality=100&strip=all&ssl=1"/>
6) Insert the SD card on your Pi. Connect an Ethernet cable and power it up.
7) After a few minutes you should be able to access Home Assistant user interface from any device on the same local network. You just need to type on the browser http://hassio.local:8123 or go to  http://your-pi-ip-address:8123 by replacing your-pi-ip-address with your Raspberry Pi IP address. If you don’t know how to find your Raspberry Pi IP address, check this post.
8) Be patient, the installation takes about 20 minutes (or more) to download all dependencies it needs for Home Assistant. While it is being installed, you’ll see the following on your browser window. Note: sometimes the screen below doesn’t load, but the installation is still continuing in the background. Let it complete the installation.
<img src="https://i0.wp.com/randomnerdtutorials.com/wp-content/uploads/2017/09/home-assistant-installation-wait.jpg?w=233&quality=100&strip=all&ssl=1"/>
9) Once it’s done, your Raspberry Pi will auto reboot, so you have to wait another 3 minutes. Then, refresh your web page and you should see the Home Assistant user interface default view. 
10) Explore the <a href="https://demo.home-assistant.io/#/lovelace/0" target="_blank"> Demo from home-assistant-community</a> Navigate through each tab and explore what’s inside.  
