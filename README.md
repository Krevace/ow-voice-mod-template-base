# OW Voice Acting Mod Addon Template Base

This is a template for making your own addon to the [Outer Wilds Voice Acting Mod](https://github.com/Krevace/ow-voice-mod)! Why would you want to do this? You can swap the voices already in the mod with your own or even add custom voice lines if you're developing a mod that adds custom dialogue to the game.

# Guide

If you're new to modding, use this [template](https://github.com/Krevace/ow-voice-mod-template) instead.
<br>

There's only a few things you need to know for this template. 
<br/>

* Putting in your voice lines is incredibly easy. Just drag your files into the `assets` folder and build the project. If you don't know the filenaming convention, check out the [Discord](https://discord.gg/daHHqkKChm), where there's a complete video and text tutorial to guide you through the process.
* If you want to change the custom credits for the mod, edit the `credits.xml` document in the `assets` folder. Line `171` is where the custom credits begin. Simply find the character(s) that you're patching and swap your name in. Or, if you're adding custom dialogue, then create a new line with `<spacer />` and `(REALNAME)#(CHARACTERNAME)`.
