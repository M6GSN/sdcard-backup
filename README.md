# backing up your Raspberry Pi SD

This need to be done on a Linux machine


this we will need to use the Linux terminal

Create a folder called backup by running `mkdir backup` them move in ti this folder by running  `cd backup`

now we need to grab the script that will shrink the image we will be creating shortly



with your SD card plugged in run df -h then plug in your SD and notice the difference you should see an entry starting /dev/sd we need to make a note of this in the example I will be using it will be /dev/udb1


we ned to run the foloowing commands
`sudo dd if=/dev/sdc of=SDCardBackup.img`
