---
title: 'nhlbot'
date: 2019-02-11T19:30:08+10:00
hasParent: true
draft: false
weight: 31
---

## Purpose

The `nhlbot` is your best friend when you're into hockey stats. There are plenty of commands to get some player or team stats, get info when the next games are, to see what the cap hit of a specific player is or also some MLB commands. It reacts to all commands that start with `!`. Please be aware that all the data is coming from APIs that are lacking in some aspects. Therefore, if incorrect data is shown, it generally means that the API is delivering incorrect data, which is something that can not be influenced and/or changed by `nhlbot`. It works with what it gets.

## Notable Commands

#### `!help`

Once called with `!help`, the bot will pm you all commands that are available. For detailed instructions for each command, you can call `!help <command>` but that is also explained to you with a list of all existing commands when you simply call `!help`.

#### `!gameday <YYYYMMDD>`

The gameday command gives you a list for all games that are scheduled for today, no matter which team, in the NHL. The date parameter is optional and it defaults to today. There is the same command for the MLB which works exactly the same, it can be called via `!gamedaymlb`

#### `!next <three letter team identifier>`

This will give you the date, time and opponent of the next scheduled game of the given team. The parameter is optional and defaults to the Blues. 

#### `!nhlplayer <name>`

Requests basic information like height, weight, age and current team of the given player. As the name suggests, it is limited to players currently playing under contract of an NHL team. If you need a more general, global search, you can omit the `nhl` part and just use `!player <name>`. Please be aware that the API results are very iffy and can appear to be very random.

#### `!playerstats <name> <year>`

This command yields the player's basic stats for the given year (the given year is used for the start of the season year). The year can be omitted to select the current season. If you want some team stats, you can follow the same logic with `!teamstats`.

#### `!addme`

`nhlbot` has a reminder functionality, that pms you 30 minute before a Blues game. In case you want to be reminded of upcoming games, just use `!addme` and the bot will let you know that you have been added to the list of people to be reminded. At any time, you can remove yourself from this list with:

#### `!removeme`

Basically the opposite command to `!addme`. With this command you're deleted from the list of people to reminded before a game start. Once you've executed the command, the bot will let you know if the removal has been successful. 

## Ideas and Feedback

If you have any suggestions for improving or extending the bot, feel free to contact `zonk` with your ideas! Same goes for issues with the bot. If the bot is spamming you, for example with a game reminder, just put the bot on ignore and `zonk` will have a look at it asap. As already said, please be aware that all the information is supplied via APIs. If they deliver incorrect information, there is nothing that can be done. 
