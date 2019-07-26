# 🥒 kara-food 🥖

## Getting started

All you need to do is to create two files in your home directory. `bot-token`, which contains your own bot's token, and `bot-target`, which contains the id of the user/group/channel you wish to send the messages to (e.g. `@alice`, `123someid` or `@somechannel`).

```
touch ~/bot-token
touch ~/bot-target
```

The program is divided in two parts based on functionality. The script called `bot-say` sends messages using Telegram's bot API, and `kara-food` acquires today's food menu from Sodexo's web site, and then sends it using `bot-say`.

Adding the scripts to your `$PATH` can prove useful if you wish to send messages through your bot at any time using `bot-say "<some message>"`.
