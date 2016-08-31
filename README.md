# Motion-orangePI

ownload image Armbian_5.14_Orangefromhttp://www.armbian.com/orange-pi-one/   
pione_Ubuntu_xenial_3.4.112 

extract it

download on 4/8 GB SD card using  Pi Filler-2  utility

ssh root@192.168.1.80  find ip using whoisonmywifi app
password:1234

change it follow instruction 

sudo apt-get install motion  

if get any error for dpkg give command  sudo apt-get -f install motion

sudo apt-get install motion  if first time not successful

after that follow instruction on 

sudo apt-get install cheese

https://www.maketecheasier.com/setup-motion-detection-webcam-ubuntu/

and 

http://www.cnx-software.com/2015/09/26/how-to-use-orange-pi-camera-in-linux-with-motion/

to remove HDMI support from orangePI one
https://www.olimex.com/forum/index.php?topic=1004.0
refer to cover back to bin 
http://www.imajeenyus.com/computer/20130301_android_tablet/android/fex2bin_etc.html

if any ssh error for connection refused
ssh-keygen -R "your ip address" 
