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



##Requirements

1. Latest version of Ansible - http://docs.ansible.com/ansible/intro_installation.html
2. Latest version of Raspbian - https://www.raspberrypi.org/downloads/raspbian/
3. Raspberry Pi (Recommended Raspberry Pi 2 Model B)



##Installation
  
```bash
git clone https://github.com/x2c/homebridge-ansible-pi.git
cd homebridge-ansible-pi
nano hosts (modify ip address to point at your raspberry pi)
./run-ansible.sh
SSH password: (default password raspberry)

``` 
