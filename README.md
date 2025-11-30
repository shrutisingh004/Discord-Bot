# Discord-Bot
### Description

A Bot which messages everyone in a Discord Server, if the member has DM's off or they have blocked the bot, they cannot be messaged

#### Commands
- `send <message>` Sends the message to all the members' DMs.
- `dm <member> <message>` Sends the messsage to the mentioned member's DMs.
- `help <optional-command-name>` Displays the available commands, you can provide a command name to get more info on the command
- `latency` Displays the latency / ping

#### Note: The bot cannot DM **_bots_**, **_the members who either have their DMs turned off_** or **_the members who have blocked the bot_**.

#### Features
- You can turn off the bot logging after each DM in the command `send`, by setting the **_`log_dms`_** to **_`off`_** or **_`disabled`_** in **_`config.json`_**
- You can adjust or even remove the ***delay*** (**_delay_** in between the multiple DMs) according to your will in ***`config.json`***(in seconds).

#### Note : The ***more is the delay***, ***the lesser is the chance of your bot getting rate limited*** **(5msgs - 5s is the rate limit for messages)**.
