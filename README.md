# RapidMSCS
Get a minecraft server on your RPI faster than anything.(This statement is prob. outdated)
Preconfigured Minecraft Java server utilizing MSCS. Easier than tedious typing.
This OS is just the installation script.
I don't own MSCS, so please check out https://minecraftservercontrol.github.io/docs/mscs (and don't ban hammer me!)
If you post an issue with MSCS here, I'll just post a link to their troubleshooting guide. I'll still fix OS-level issues.

Once installed, run this command to create a new world: mscs create [world] [port]

Replace [world], with the name of your world, choose a port and replace [port] with it. After creation, run this command: mscs start [world].

The world should shut down, so accept the EULA in /opt/mscs/worlds/myWorld.
