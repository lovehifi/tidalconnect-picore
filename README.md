# Tidal Connect for PiCorePlayer
>

piCorePlayer is a very small Music OS, only about a few tens of MB in size, and operates entirely on RAM.
Installing Tidal Connect on piCorePlayer can significantly increase the size of your OS, adding about 100MB. If you're not too concerned about that, give it a try. This version only supports 32-bit.
>
>
------------
To get it working on piCorePlayer (version 8.2.0), you first need to go to Extensions and select Load to add the necessary extensions:
> avahi.tcz
>
> ipv6-netfilter-5.15.35-pcpCore-v7.tcz
>
----------
Install
Coming soon...
>
----------------
After installation, you need to perform the following steps:

Open the Tweaks page and add the following
>
User command #1:
> /usr/local/etc/init.d/avahi start

User command #2:
> /home/Tidal-Connect-Armv7/tidal.sh
>
Next, go to the Main page and click on Backup. After completing that, reboot your system.
