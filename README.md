# drctrl

## Background
This is a LUA script meant to be used with the ComputerCraft and Draconic Evolution mods for Minecraft 1.7.10. ComputerCraft adds computers to Minecraft which can run LUA scripts to interact with the world and content from other mods. Draconic Evolution adds various late-game tech and gear, including a massive reactor for producing power. This LUA script runs on a ComputerCraft computer to manage the Draconic Evolution reactor, optimizing power output and preventing any possible meltdowns. Additionally, by using ComputerCraft touchscreen monitors, you can see real-time stats about the reactor and dynamically change the desired power output.

## Description
This program is an edit of acidjazz's Draconic Reactor control code. I still use his library and most of his code is unchanged, however I did fix some math and make the program more robust. This is what I am currently using for my reactors and so far it has been more accurate. For setup instructions, go to acidjazz's original repository here: https://github.com/acidjazz/drmon

To install the script run the command: "pastebin run cD5w1sa9 install" on the advanced computer in charge of the reactor and reboot it. The script runs automatically on reboot.

You can edit some of the variables in the code at the top, such as the maximum safe temperature, minimum safe field percent, minimum safe fuel percent, and more.
