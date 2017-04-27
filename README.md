
# [Pvresan-Bot](https://t.me/BugSecurity)

Professional Pvresan-Bot Based On NEW Api


* * *

## Commands

| Use help |
|:--------|:------------|
| [/]help | just send help in your group and get the BoT commands |

**You can use "/" (help) to begin all commands

* * *

# Installation

```sh
# Let's install the self-bot.
sudo apt-get update
sudo apt-get install lua5.1 luarocks lua-socket lua-sec redis-server curl 
sudo luarocks install oauth 
sudo luarocks install redis-lua 
sudo luarocks install lua-cjson 
sudo luarocks install ansicolors 
sudo luarocks install serpent
git clone https://github.com/Comodo21/pvresan
cd pvresan # Add your bot to file token/Information config.lua
screen lua bot.lua 
```
### One command
To install everything in one command, use:
```sh
cd $HOME && git clone https://github.com/BeyondTeam/Self-BotV2.git && cd Self-BotV2 && chmod +x beyond.sh && ./beyond.sh install && ./beyond.sh
```

* * *

### Sudo And Bot

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    157059515,
    0,
    YourID
  }
```
add your ID at line 4 and 131 in bot.lua
Then restart or reload.

# Support and development

More information [GP Development](https://t.me/joinchat/AAAAAEGGbzvkH92lwfah7g)

# Special thanks to
[Ex3ER](https://telegram.me/Ex3ER)


* * *


### Our Telegram channel:

[BugSecurity](https://t.me/BugSecurity)


