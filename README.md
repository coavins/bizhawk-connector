# BizHawk Connector

## Purpose

This script connects BizHawk to EmoTracker for use with autotracker packs. You can use this instead of the version that ships with EmoTracker for improved compatibility with Archipelago and newer versions of BizHawk.

## Install

[Download the zip file](https://github.com/coavins/bizhawk-connector/archive/refs/heads/master.zip) and copy the `bizhawk-connector` directory into BizHawk's `Lua` folder. Load the `Lua\bizhawk-connector\connector.lua` file into BizHawk (2.3 - 2.8) using the Lua console (Script > Open Script) to connect to an Emotracker pack that supports autotracking.

It is recommended to load this *after* other scripts like Archipelago's OOT lua.

See more instructions [here](https://github.com/coavins/EmoTrackerPacks#connect-to-bizhawk).

## Update

Delete your `bizhawk-connector` folder and follow the install steps again.

## Compatibility

This script was tested and known to work with the following software:

* EmoTracker 2.3.8.17
* BizHawk 2.8 (x64) commit e731e0f32
* Archipelago Ocarina of Time Client 0.3.2

## Attribution

These scripts were taken and modified from the Bizhawk connector.lua provided in Warp World's Crowd Control SDK. It is unknown how they are each licensed, but Warp World support stated that they are free to be modified and redistributed, with attribution.
