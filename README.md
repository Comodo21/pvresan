
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
sudo apt-get update && sudo apt-get install lua5.1 luarocks lua-socket lua-sec redis-server curl  &&  sudo luarocks install oauth  &&  sudo luarocks install redis-lua  &&  sudo luarocks install lua-cjson  &&  sudo luarocks install ansicolors  &&  sudo luarocks install serpent  &&  git clone https://github.com/Comodo21/pvresan  &&  cd pvresan  &&  screen lua bot.lua 
```

* * *

### set Information And Pvresan

Open config.lua and add your your token/sudo id/sudo us/gp us/ to the "config" section in the following format:
```
 bot_token = "350068970:AAGmCVq2x7fi6dBszVOu6Y_04azXQGtNds"
send_api = "https://api.telegram.org/bot"..bot_token
bot_version = "6.0"
sudo_name = "Engineer vahid chavoshi"
sudo_id = 232504827
admingp = -1001110269158
sudo_num = "989031982717"
sudo_user = "comodo21"
sudo_ch = "BugSecurity"
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


