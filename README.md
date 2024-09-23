> 🇪🇳 README in English available [here](README-EN.md)
## Рекомендации по установке

## Binance-Moonbix-bot [ссылка](https://t.me/Binance_Moonbix_bot/start?startApp=ref_896333795&startapp=ref_896333795&utm_medium=web_share_copy)

##  Используйте с PYTHON 3.10 - 3.11.5 

## Функционал  
| Функционал                  | Поддерживается  |
|-----------------------------|:----------------:|
| Многопоточность             |        ✅        |
| Привязка прокси к сессии    |        ✅        |
| Сбор дневной прибыли        |        ✅        |
| Авто игра                   |        ✅        |
| Поддержка pyrogram .session |        ✅        |


## Настройки .env файла
| Настройки |                                  Описание                                  |
|----------------------------|:--------------------------------------------------------------------------:|
| **API_ID / API_HASH**      |   Данные платформы, с которой запускать сессию Telegram (сток - Android)   |     
| **AUTO_TASK**              |                 Прохождение дневных заданий (дефолт: True)                 |
| **AUTO_PLAY_GAME**         |                         Авто игра (дефолт: True)                          |
| **USE_PROXY_FROM_FILE**    | Использовать-ли прокси из файла bot/config/proxies.txt file (True / False) |


## Предустановки
Перед началом убедитесь что у вас установлен питон:
- [Python](https://www.python.org/downloads/) **version 3.10 - 3.11.5**

##  Получение API ключей
1. Перейдите на сайт [my.telegram.org](https://my.telegram.org) и войдите в систему, используя свой номер телефона.
2. Выберите **"API development tools"** и заполните форму для регистрации нового приложения.
3. Запишите `API_ID` и `API_HASH` в файле `.env`, предоставленные после регистрации вашего приложения.

## Установка
Вы можете скачать [**repository**](https://github.com/Re-Diss/Binance-Moonbix-bot) клонированием на вашу систему и установкой необходимых зависимостей:
```shell
git clone https://github.com/Re-Diss/Binance-Moonbix-bot
cd Binance-Moonbix-bot
```

Потом вы можете запустить автоматическую установку:

Windows:
```shell
run.bat
```

Linux:
```shell
run.sh
```

# Linux ручная установка
```shell
python3 -m venv venv
source venv/bin/activate
pip3 install -r requirements.txt
cp .env-example .env
nano .env  # Here you must specify your API_ID and API_HASH, the rest is taken by default
python3 main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/Binance-Moonbix-bot >>> python3 main.py --action (1/2)
# Or
~/Binance-Moonbix-bot >>> python3 main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```

# Windows ручная установка
```shell
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
copy .env-example .env
# Here you must specify your API_ID and API_HASH, the rest is taken by default
python main.py
```

Также для быстрого запуска вы можете использовать аргументы, например:
```shell
~/Binance-Moonbix-bot >>> python main.py --action (1/2)
# Or
~/Binance-Moonbix-bot >>> python main.py -a (1/2)

# 1 - Run clicker
# 2 - Creates a session
```


