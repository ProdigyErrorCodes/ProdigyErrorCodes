# Code 418

HTTP 418 is an anticheat to prevent people using hacks to spawn in unusual loot.
- Attempting to obtain [> 10M gold](https://github.com/Prodigy-Hacking/ProdigyMathGameHacking/commit/08e3866c92b4e158d97369784461a698383e2ce1) and then finishing a battle.
- Spawning in OG epic buddies with [WCM](https://github.com/Prodigy-Hacking/ProdigyMathGameHacking/tree/master/willsCheatMenu)/[PHEX](https://github.com/Prodigy-Hacking/ProdigyMathGameHacking/tree/master/PHEx) or the [Prodigy Dashboard](https://prodigy-dashboard.hostedposted.com).
- Getting Member Stars

# "Inactivity" list

The Inactivity Kick is sometimes used as an anticheat to prevent people from cheating.
- Happens when you use `Win Battle` in the Arena and open a chest.
- Attempting to obtain [> 10M gold](https://github.com/Prodigy-Hacking/ProdigyMathGameHacking/commit/08e3866c92b4e158d97369784461a698383e2ce1) and then finishing a battle.
- Signing in to two accounts without incognito; another profile, browser, computer, etc.
- Also happens when you go AFK for a while.

# Other error codes

## Error code 20
- Caused by system clock being offset 2 hrs+.
- Caused by using a used login token.

## Error code 36
- Caused by bad internet connection (can be reproduced without hacks).

## Error code 48
- Currently unkown, happened to someone when attempting to log into Prodigy, even though they have never used hacks.

## Error code 72
- Caused by an ambiguous error due to hacks, usually in console, unsure of consistent cause.
- Confirmed example: Running `_.player.backpack.data.hat = [null];`, character save, and logging back in.

## Error code 84
- `Error loading player spells/skills.`

## Error code 403
- Happens after using `Disbale Inactivity Kick` in WCM (PHEX) and then being inactive.
- Happens when you close the Inactivity Kick popup.

## Error code 404
- This used to happen when someone tried to open the HTML Elements or Javascript console (doesn't happen anymore)

## Error code 500
- Happens when you use the [Prodigy Dashboard](https://prodigy-dashboard.hostedposted.com) and sign into an account with pending email confirmation.
- I don't know how to fix this error.


###### _Last Updated February 12, 2022 by [40287#28](https://github.com/donaldli2020)_
