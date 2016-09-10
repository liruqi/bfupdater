# Bigfoot WoW plugins Updater for Mac

## Introduction

This project is the updater for [Bigfoot World of Warcraft plugins](http://bigfoot.178.com/wow/) on Mac since Bigfoot client doesn't support Mac and Mac WoWer can only update plugins by hand every time the plugins are updated.

## Usage

Anytime Bigfoot tips "plugins are out of date" in game, you can run `update.sh` to update you plugins.

NOTE: you need to specify your path to WoW by hand before the first time you run `update.sh`(at the first several lines).
If your path is `/Users/wzh/software/games/World of Warcraft`, replace the `wow_parent_path` value with `/Users/wzh/software/games`.
I assume Mac user knows how to get the path to his WoW.

To run this `update.sh` tool, simply open your terminal, change the working direcroty to this project, and type `./update.sh`. Wait for the update.

## Error Reporting

If you observed message like "ERROR: xxx" in terminal or system tips error, please report at the [project issue site](https://github.com/jackwish/bfupdater/issues).

## Backup

Copyright 2016 WANG Zhenhua.
