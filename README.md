# BizHawk Connector

## Purpose

Use this script to connect BizHawk to EmoTracker for use with autotracker packs.

This was forked from Crowd Control's connector.lua to fix bugs and improve support for Archipelago. Changes were made to reduce conflicts with AP's OOT lua, in order to allow running an autotracker while connected to an Archipelago game.

## Usage

Simply download and extract anywhere. Load the `connector.lua` script into BizHawk (2.3 - 2.8) to connect to an Emotracker pack that supports autotracking. See more detailed instructions [here](https://github.com/coavins/EmoTrackerPacks#connect-to-bizhawk).

It is recommended to load this *after* other scripts like Archipelago's OOT lua.

## Compatibility

This script was tested and known to work with the following software:

* EmoTracker 2.3.8.16
* BizHawk 2.8 (x64) commit e731e0f32
* Archipelago Ocarina of Time Client 0.3.1

## Attribution

These scripts were taken and modified from the Bizhawk connector.lua provided in Warp World's Crowd Control SDK. It is unknown how they are each licensed. Works provided by Warp World are known to be freely modified and redistributed, with attribution.
