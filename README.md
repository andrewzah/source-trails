## About

This plugin was adapted from one I found on alliedmods, Tf2 Trails I think.

The main difference is it shows trails once player velocity >= 700 hammer units, and kills it once player velocity >= 550 hammer units. Players can use `!trail` to configure what trail they want to use.

It's very rough, so cleaning it up to use convars, etc, would be appreciated.

I adapted it for Open Fortress but it should work for CS:GO, TF2, etc.

## Install

* Put the script in addons/sourcemod/scripting and compile it with ./compile.sh.

* Put the config in addons/sourcemod/configs and modify to your liking.

* Put the sprites in materials/sprites/store/trails in your server directory

* **Put the sprites in your FastDL folder as well**, otherwise your players won't be able to see any trails.