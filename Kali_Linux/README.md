# Kali Linux
Here you will find instructions on how to download and setup your very own Kali Linux machine: <br>
<br>
If you are unfamiliar with what virtualbox, Linux, or Kali Linux then head on over to the "where to start" directory where I have added some great links to videos and readings on those topics. I'll even give you a link right to it, here: [Let's Learn](/0_Where_To_Start) <br>
<br>

## Before you get started
Before you get started, I recommend downloading a download manager. It is not necessary but can be helpful. You can download a popular and free one called [Free Download Manager](https://www.freedownloadmanager.org/). I mean, that name could not be better. If you ever google "hey I want a free download manger", boom that's the first thing that is going to pop up. If you're not sure why you should get it maybe this article will help. <br>
[Why You Should use a Download Manager](https://www.hellotech.com/blog/use-download-managers)<br>
<br>

## Virtualbox
If you don't already have virtualbox then go ahead and download it. We all use it so if you have any trouble with it don't be afraid to ask for help! <br>
[VirtualBox](https://www.virtualbox.org/) <br>
<br>

## Kali Linux
Once you have Virtualbox downloaded it is time to download Kali Linux. Scroll down to the machine images and click the + button on the virtualbox images tab. Download the OVA file and double-click to open it. It will open virtualbox for you and then click "import" and wait for it to download. <br>
[Kali Linux](https://www.offensive-security.com/kali-linux-vm-vmware-virtualbox-image-download/#1572305786534-030ce714-cc3b)<br>
<br>

## After You Import Kali
The default user has been changed to a standard, unprivileged user. The default username and password are both "kali".<br>

Prevent Kali from going idle:
- Click on the power button (top right), then "Power Manager Settings", and then Display
- Change all of them to "never"
- Go to security, change the same thing, if you want to. 

To change the password:
- sudo su (su meaning switch user)
- Type in the password ("kali")
- passwd root (we are changing the password for the root user, you.)
- type in your new password

Now it is time to update. You will need to be patient for this step. Open up a terminal and type in the following:
- apt update && apt -y full-upgrade

<br>
After all of that you should be set. When powering down the machine do not use the x button in the corner. Doing that is like pulling the plug on your computer when it is on. You are going to go to virtualbox, right click on the machine, then close, then power off.<br>
<br>

## Windows won't let you power on Kali Linux?
If you are using Windows then you might come across an error in which the machine won't even start. Does it say something like "Failed to open a session for the virtual machine"? If so, try the following and see if it fixes the issue. If it doesn't fix the issue then you can always message in the general slack and ask for help!<br>

What you are going to want to do is first close out your virtual machine manager, in this case it should be virtualbox. Go to Windows Search and type in "features". Click on "Turn Windows features on or off". Now you are going to disable the following. If any of them are already disabled, then you can skip those:
- Virtual Machine Platform
- Windows Defender Application Guard
- Windows Hypervisor Platform
- Windows Sandbox

Click ok and restart your computer. 
