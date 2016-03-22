#Homebridge Ansible Pi

![alt text](http://i.imgur.com/tT8Wa4H.jpg "HomeKit")
![alt text](http://i.imgur.com/1uO4SZL.png "Raspberry Pi")
![alt text](http://i.imgur.com/i866cOb.png "Ansible")



##Introduction
HomeBridge Ansible Pi is an automated script for installing the excellent 
[HomeBridge](https://github.com/nfarina/homebridge "HomeBridge Githhub") package onto a Raspberry Pi.
Homebridge enables IOT devices to be added and controlled by Siri that would normally not be supported by Apple's Homekit at all. These devices include:
* Lockitron
* Nest
* Sonos
* SmartThings
* SoundTouch
* Wemo

[HomeBridge-hdmi](https://github.com/x2c/homebridge-hdmi "HomeBridge HDMI") is now automatically installed and configured as part of the set-up process. This enables you to plug your Raspberry Pi directly into your HDMI TV or AV Amp and issue comannds like "Hey Siri, turn the TV on"

##Requirements

1. Latest version of Ansible - http://docs.ansible.com/ansible/intro_installation.html
2. Latest version of Raspbian - https://www.raspberrypi.org/downloads/raspbian/
3. Raspberry Pi (Recommended Raspberry Pi 2 Model B)



##Installation
  
```bash
git clone https://github.com/x2c/homebridge-ansible-pi.git
```
```bash
cd homebridge-ansible-pi
```
```bash
nano hosts (modify ip address to point at your raspberry pi)
```
```bash
./run-ansible.sh
```
```bash
SSH password: (default password raspberry)
```

##Configure Homebridge on iOS iPhone/iPad
Currently there are no official apps for adding HomeBridge devices to Apple's HomeKit.
A number of third party apps are available which will enable you to add your new HomeBridge devices to Siri:

* [Insteon+](https://itunes.apple.com/US/app/id919270334?mt=8 "Insteon+ HomeKit App") Price : Free
* [Lutron](https://itunes.apple.com/us/app/lutron-app-for-caseta-wireless/id886753021?mt=8 "Lutron HomeKit App") Price : Free
* [MyTouchHome](https://itunes.apple.com/us/app/mytouchhome/id965142360?mt=8&at=11lvmd&ct=mhweb "MyTouchHome HomeKit App") Price : $1.99
* [Devices](https://itunes.apple.com/us/app/devices/id966877433?mt=8 "Devices HomeKit App") Price : $2.99

Adding HomeBridge devices to Homekit the default code is **031-45-154**
