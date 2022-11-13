# Server Setup and Configuration
In this guide we will teach you how to install Crucible. 
To use Crucible make sure you have `Java 8` installed, in this guide
we will be under the assumption java is on your global path, and you know the basics of a terminal.


### Create a fresh Crucible server
* Download the latest Crucible version [here](https://github.com/CrucibleMC/Crucible/releases/tag/v5.4)
* Drop the `Crucible-1.7.10-X.X.jar` (X being the current version number) on your server root
* To run Crucible you can use `java -jar Crucible-1.7.10-X.X.jar`, to avoid having to open a terminal every time you want
to run it you can create a batch/sh script.

* For Windows, create a file named `start.bat` alongside the Crucible jar with the following content:
```bat
@echo off
java -jar Crucible-1.7.10-X.X.jar
PAUSE
```

* For Linux and Mac, create a file named `start.sh` alongside the Crucible jar with the following content:
```shell
#!/bin/bash
java -jar Crucible-1.7.10-X.X.jar
```
* You now can run the launch scrip.


### Update a Thermos server
While we recommend moving to plain Crucible, we understand it comes with a bounder to change a working server to a new 
software that may break it. For those who wish to receive important bug fixes without having to deal with any breaking 
changes we offer the reflux releases, a drop in replacement for Thermos.
* Downloaded the latest reflux release [here](https://github.com/CrucibleMC/Crucible/releases/tag/reflux-v1).
* Backup your server, just in case something unexpected happens.
* Replace your Thermos jar with the Reflux jar

If for some reason your server do not start or something odd breaks, please make an issue [here](https://github.com/CrucibleMC/Crucible/issues) or join our [discord](https://discord.gg/jWSTJ4d)