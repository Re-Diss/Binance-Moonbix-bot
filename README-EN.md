
## Recommendation before use

# The bot [link](https://t.me/Binance_Moonbix_bot/start?startApp=ref_896333795&startapp=ref_896333795&utm_medium=web_share_copy)


#  Use PYTHON 3.10 - 3.11.5 

## Features  
| Feature                                                     | Supported  |
|---------------------------------------------------------------|:----------------:|
| Multithreading                                                |        ✅        |
| Proxy binding to session                                      |        ✅        |
| Auto checkin                                                  |        ✅        |
| Auto play game                                                |        ✅        |
| Support for pyrogram .session                                 |        ✅        |


## Settings
| Settings | Description |
|----------------------------|:-------------------------------------------------------------------------------------------------------------:|
| **API_ID / API_HASH**      | Platform data from which to run the Telegram session (default - android)                                      | 
| **AUTO_TASK**              | Auto do task (default: True)                                                                                  |
| **AUTO_PLAY_GAME**         | AUTO PLAY GAME (default: True)                                                                                |
| **USE_PROXY_FROM_FILE**    | Whether to use a proxy from the bot/config/proxies.txt file (True / False)                                    |


## Prerequisites
Before you begin, make sure you have the following installed:
- [Python](https://www.python.org/downloads/) **version 3.10 - 3.11.5**

## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Installation
You can download the [**repository**](https://github.com/Re-Diss/Binance-Moonbix-bot) by cloning it to your system and installing the necessary dependencies:
```shell
git clone https://github.com/Re-Diss/Binance-Moonbix-bot
cd Binance-Moonbix-bot
```

Then you can do automatic installation by typing:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux manual installation
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

You can also use arguments for quick start, for example:
```shell
~/Binance-Moonbix-bot >>> python3 main.py --action (1/2)
# Or
~/Binance-Moonbix-bot >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows manual installation
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

You can also use arguments for quick start, for example:
```shell
~/Binance-Moonbix-bot >>> python main.py --action (1/2)
# Or
~/Binance-Moonbix-bot >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

Origin reference - https://github.com/vanhbakaa/moonbix-bot
