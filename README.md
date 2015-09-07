![project logo](http://res.cloudinary.com/drsedusa/image/upload/v1441593037/raspi-ionic-logo_cs1d33.png)

# Synopsis
A simple IOT project using the Ionic Framework to create a simple app that turns on an LED on a breadboard connected to Raspberry Pi.

# Motivation
I decided to create this project after I learnt about how to use Node,js to interact with the Raspberry Pi GPIO pins.  I also decided to build a simple mobile app using the Ionic Framework to interact with the Raspberry Pi via a simple API call.

#Installation
For anyone who has never played around with a Raspberry Pi here's a great <a href="https://www.raspberrypi.org/wp-content/uploads/2012/04/quick-start-guide-v2_1.pdf" target="_blank">quick start guide</a> from the official <a href="https://www.raspberrypi.org/" target="_blank">raspberrypi.org</a> website.
The project assumes that you have a Raspberry Pi at your disposal (any of the models) and that you are able to run it 'headless' (i.e. with no keyboard or display).  
Here is a <a href="https://www.raspberrypi.org/forums/viewtopic.php?f=91&t=74176" target="_blank">tutorial on how to setup the Raspberry Pi 'headless'</a>.

###Installing Node.JS on your Raspberry Pi
You will need to have Node.js installed on your Raspberry Pi before proceeding with this project.  You can follow the steps in this <a href="http://weworkweplay.com/play/raspberry-pi-nodejs/" target="_blank">tutorial on how to setup Node.js on your Raspberry Pi</a> or simply type out the following commands after you ssh into your raspberry pi.
```
$ > wget http://node-arm.herokuapp.com/node_latest_armhf.deb
$ > sudo dpkg -i node_latest_armhf.deb
```

### Installing Git
```
$ > sudo apt-get install git
```
After installing Git on your Pi I recommend reading you check out the <a href="http://git-scm.com/book/en/v2" target="_blank">Pro Git book</a> (by Scott Chacon and Ben Straub) to learn how to use it.
In order to pull code from Github you will need to add your SSH key to your Github settings (after you create a Guthub account of course :-)).  You can obtain your SSH key by running the following commands in terminal on your Pi.
```
$ > ssh-keygen -t -rsa  
$ > cat ~/.ssh/id_rsa.pub
```






**The video below shows how the app interacts with the Raspberry Pi.**

<a href="http://www.youtube.com/watch?feature=player_embedded&v=9yw8BysEuNY
" target="_blank"><img src="http://img.youtube.com/vi/9yw8BysEuNY/0.jpg" 
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>


