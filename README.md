# Minecraft Server on Google Cloud
In this Project, I will teach you the way to host your Minecraft Server on Google Cloud.

**Features :**
* Support Vanilla Bedrock Server
* Support Vanilla Java Server

## Need Help?
* Join our [**Discord Server**](https://discord.gg/XahP8hZhB8)

## Service Used
* [**PLAYIT.GG**](https://playit.gg)
* [**Google Cloud**](https://cloud.google.com)

## Setup your Minecraft Server
* Activate a [Google Cloud Shell](https://console.cloud.google.com)
* Clone this Github Project into the Console
```
git clone https://github.com/GGxABDUL/mc.git
```
* Go into `mc` directory
```
cd mc
```
* Allow all command excutable
```
chmod +x *
```
* Setup your Minecraft Server
```
./setup
```
* Start your Minecraft Server
```
./start
```
* Port Forward your Minecraft Server
```
./tunnel
```
## Checking your Server
* To view if your server is ready or not, use this Command
```
screen -r Server
```
* Detach the Session
> Press `CTRL + A` then press `D` 
## Join your Server
* Connect to your Server using Playit
```
screen -r tunnel
```
* Detach the Session
> Press `CTRL + A` then press `D` 

## Enable Cracked Server
* This method only for a Third Party Launcher and Cracked Minecraft
* Go to `server.properties` to enable `Cracked Server`
```
cd mcserver
```
```
nano server.properties
```
* Disable Online Mode
```
online-mode=false
```
Then, to save it, Press `CTRL + W` and press `Y`
* Go back to the main project by execute this command
```
cd ..
```

## Stop your Minecraft Server
* Execute this Command to stop the Server
```
./stop
```
## Uninstall your Minecraft Server
* Execute this Command to uninstall the Server
```
./uninstall
```
## Keep your Server Online
> There are only **ONE** way to keep your Server Online. You have to keep the website **OPEN** or the Server will **STOP**!

## CREDIT
* > Owner of this Code - [NiXE xD](https://www.youtube.com/channel/UCK9F2ptByYjY4UOqMn4UXNQ)
