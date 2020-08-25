---
title: 'Hockey Commands'
date: 2019-02-11T19:30:08+10:00
hasParent: true
draft: false
weight: 1
---

## List of hockey-related commands

#### `?req add St. Louis Blues`

With this command you can self-assign the `St. Louis Blues` role, which gets pinged whenever a Blues game starts or when the intermission is over and the game continues. As described in the general Bot commands, you can relinquish that role at any time with `?req rem St. Louis Blues`.

#### `?nhl`

This command is the root command of all the hockey commands. If you enter just that and nothing else, you will get an overview of all the available hockey commands. Some of the more useful ones are described in here.

#### `?nhl games [team] [YYYY-M-DD]`

You can omit or include either team and/or the date. If you just call the command without a team name or a day, it will just output today's games. If you include a team but no date, it will give you the team's schedule which you can click through. You can also only include a date with the command, and you get to see which games are on that specific date. Last but not least, you can include team and date and see which games this team had or will have on this date.

#### `?nhl players <team>`

As the name suggests, it returns the current roster of a team and their stats.

#### `?nhl player <last name>`

Returns stats for this specific player for the current season.

#### `?nhl standings [division name]`

Returns an overview of the current standings in each divison. Comes with little interactive emojis, so you can scroll through all the divisions. Add the divison name to the command to immediately display the divison you're interested in.