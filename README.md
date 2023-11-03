# Tidal Connect for PiCorePlayer
>

piCorePlayer (piCorePlayer v8.2.0) is a very small Music OS, only about a few tens of MB in size, and operates entirely on RAM.
Installing Tidal Connect on piCorePlayer can significantly increase the size of your OS, adding about 100MB. If you're not too concerned about that, give it a try. This version only supports 32-bit.
>
>
------------
Install Tidal Connect.
> 
> wget -O - https://raw.githubusercontent.com/lovehifi/tidalconnect-picore/main/install.sh | sh
>
----------------
After installation, you need to perform the following steps:

Open the Tweaks page and add the following
>
> In the tweaks page, Shairport-sync to Yes.
>
User command #1:
> /usr/local/etc/init.d/avahi start

User command #2:
>  /home/tc/Tidal-Connect-Armv7/tidal.sh start
>
Click button Save, reboot your system.
>
----------------------------
I've created a build of the IMG piCorePlayer 8.2, and I've added Tidal Connect to it. You can try using it if you want.
>
Download: https://drive.google.com/file/d/1Ox2RJ8kQ_XSpZFzUBxtDSs5w46JZDmm4
>
------------------------------
I gather them from these repositories to make them easy to use.
>
https://github.com/GioF71/tidal-connect
>
​https://github.com/TonyTromp/tidal-connect-docker
>
​https://github.com/vcucek/ifi-tidal-moode
