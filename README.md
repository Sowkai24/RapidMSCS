# RapidMSCS
Download: https://github.com/Sowkai24/RapidMSCS/releases
Get a minecraft server on your RPI faster than anything.(This statement is prob. outdated)
Preconfigured Minecraft Java server utilizing MSCS. Easier than tedious typing.
This OS is just my installation script in an OS.
I don't own MSCS, so please check out https://minecraftservercontrol.github.io/docs/mscs (and don't ban hammer me!)
If you post an issue with MSCS here, I'll just post a link to their troubleshooting guide. I'll still fix OS-level issues.

Once installed, run this command to create a new world: mscs create [world] [port]

Replace [world], with the name of your world, choose a port and replace [port] with it. After creation, run this command: mscs start [world].

The world should shut down, so accept the EULA in /opt/mscs/worlds/myWorld.

# OS info

Compatible with Pi 1b(+)/2b(+)/3b(+)/4b/400

Important Note!! : The included OS zip is designed only for the Pi models listed below. The OS is a .dmg file in a .zip, so use balenaEtcher at etcher.io to write the SD card.

I recommend that you use the 4b, and with a minimum of 2GB of RAM for around 5 players, and 4 to 8GB of RAM for around 5 to 25 players. I don't recommend using USB to boot, so you may want to roll back the boot loader if you have the version with USB boot. It's also better to use the newer pi models because they have faster Wi-Fi and Ethernet. Get good cooling for your pi, like this one: https://amzn.to/2KSTUmy
A 16GB SD card should do the trick, but higher is better. The best storage for it is a Class 10, UHS-1 SD card, like this one: https://amzn.to/3j3HDZn

If you are a PC person, then run the script. That's it. Ethernet will increase performance, but it's not necessary if you have fast Wi-Fi. Put your PC somewhere it can breathe, too. Set your PC to never sleep, and only use Ubuntu, Debian, and it's derivatives. Don't use Arch, Manjaro, Fedora, or any of their derivatives. SSDs are great, so try that if you have one.
