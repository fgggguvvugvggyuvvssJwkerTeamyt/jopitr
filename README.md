# [MahDiRoO](https://telegram.me/Mr_JwKeR)


* * *


# Installation

```sh
# Let's install the bot.
cd $HOME
git clone https://github.com/jwkerteam/jopitr.git
cd jopitr
chmod +x jopitr.sh
chmod 777 auto.sh && sed -i -e 's/\r$//' auto.sh
./jopite.sh install
./jopitr.sh 
# Enter a phone number & confirmation code.
```

* * *

### launch Bot

```
killall screen
cd jopitr && screen ./jopitr.sh
```

* * *


### auto launch 
```
killall screen
cd jopitr && screen ./auto.sh
```

* * *


### Sudo

Open ./bot/bot.lua and add your ID to the "sudo_users" section in the following format:
```
    sudo_users = {
    285748689,
    0,
    YourID
  }
