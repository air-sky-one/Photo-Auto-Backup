# Photo-Auto-Backup
Auto Backup Photos and Videos from USB devices and SD Cards. Raspberry Pi 1 B - script and config 

Internet Links
--------------
* Googel Search : https://www.google.fr/webhp?sourceid=chrome-instant&ion=1&espv=2&ie=UTF-8#q=raspberry%20pi%20sd%20udevadm

* INSTALLING OPERATING SYSTEM IMAGES ON LINUX : http://www.raspberrypi.org/documentation/installation/installing-images/linux.md

* How to Mount an External Hard Drive on the Raspberry Pi – Raspian : http://www.modmypi.com/blog/how-to-mount-an-external-hard-drive-on-the-raspberry-pi-raspian

* Photo autocopy from SD card : http://larsmichelsen.com/open-source/photo-autocopy-from-sd-card/#comment-833455

* Raspberry PI tutorial SD slurping : http://bneijt.nl/blog/post/raspberry-pi-tutorial-sd-slurping/

* How can I change the date modified/created of a file? : http://askubuntu.com/questions/62492/how-can-i-change-the-date-modified-created-of-a-file

-> sudo nano /etc/udev/rules.d/99-sd-autocopy.rules
-> sudo nano /usr/local/bin/sd-autocopy
-> sudo chmod +x /usr/local/bin/sd-autocopy