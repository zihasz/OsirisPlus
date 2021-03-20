# HAS SOME MODIFICATIONS TO THE ORIGINAL VERSION


An actively maintained fork of Finz0's Osiris!
Join the discord - https://discord.gg/PmM6B68

## Build Guide

### Dependencies

JDK 8

a brain

### Windows

First, open cmd. Run `cd "<insert path to directory where you downloaded the source code>"`. 
Next, run `gradlew setupDecompWorkspace`, and then run `gradlew.bat build`. 

You can also run `blablabla.bat` and `autobuild.bat` in that order.

### Linux

First, open terminal. Run `cd "<insert name where you downloaded the source code>"`. 
Next, run `./gradlew setupDecompWorkspace`, and then run `./gradlew build`. 

The build output is in `build/libs` and ends in `-release.jar`. 
