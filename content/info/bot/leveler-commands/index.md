---
title: 'Leveler Commands'
date: 2019-02-11T19:30:08+10:00
hasParent: true
draft: false
weight: 32
---

## Intro

The bot is running a leveler system plugin that rewards active users with experience and ₵oin. If they collect enough experience, they will level up and unlock particular roles, displaying their ~~superiority~~ seniority on the server.  
In addition, each user has a public profile that they can customize. It's possible to change the colors on it, the background image and some description on it. Lastly, the users can use their currency to buy and collect little badges that they can display on their profile.  
It is important to note that the leveler plugin offers more functionality, that is not used. There is not really put any effort into maintaining the user's `rank` since it's basically the same as `profile` but with less customization. Levelup messages are hidden as well, so any customization of those is not displayed.

**Important:** Some of the commands output very long lists or have an otherwise spammy character. Please only use them in the [spam channel](../../channels/spam) or in a DM with the bot.  
Also, please be aware that there's no point in spamming messages to get more XP more quickly. There are plenty of factors that play a role how fast a user gains more XP. Just spamming messages will not necessarily give you more XP. If you try to abuse the system, you will get an XPban, meaning that you can't gain XP for a certain period of time.

## `?lvlset`

`?lvlset` is the root command to customize your profile. Here you can manage your badges as well as change other things about your profile.

### `?lvlset badge`

With `?lvlset badge available` you can get a list of all available badges that you can buy. It is also displayed how much they cost or if they're unavailable to purchase. If you decide to buy a badge, just use the `?lvlset badge buy <name>` command.

Once you've purchased a badge, you can display the badges you own with `?lvlset badge list`. On your profile you have 9 slots for badges. They're sorted by priority which you can set. After purchasing a badge, use `?lvlset badge set <name> <priority>` to display an owned badge on your profile. Higher priority is shown top left.

### `?lvlset profile`

This command lets you change all kinds of settings for your profile. Just call the command and you will get an overview of the options, since listing them here would be overkill. Just be aware that changing the background of your profile comes with a cost. A list of all backgrounds can be found with `?backgrounds profile`.

## `?profile [user]`

This command displays your current profile. If you add a user name to the command you can look at other people's profile.

## `?rep <user>`

With this command you can give a user a rep. It's similar to a like on social media. The amount of reps a user has is displayed on their profile.

## `?top [-rep]`

Displays the current standings of all users on the server and displays the top 15. If you add the `-rep` parameter, it shows the ranking by reps instead of XP.

## `?backgrounds profile`

Displays a gallery of backgrounds that you can scroll through via emoji reactions. You need the names of the backgrounds, if you want to change yours. Remember, changing your background comes with a cost.

## `?payday`, `?slot <bid>`

Regularly chatting on the server is not the only way to gain more coin. With `?payday` you can cash in that check that you deserve so badly. If you're feeling lucky, you can try to gamble and multiply (or lose) your hard-earned money with `?slot <bid>`.