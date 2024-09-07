> [<img src="https://img.shields.io/badge/Telegram-%40Me-orange">](https://t.me/roddyfred)

![img1](./.github/image/hero.png)

# Use Node.Js 18 or later

## Functionality

| Functional                            | Supported |
| ------------------------------------- | :-------: |
| Claiming mining reward                |    ✅     |
| Starting mining                       |    ✅     |
| Multithreading                        |    ✅     |
| Creating sessions with qrcode         |    ✅     |
| Using a session/query_id              |    ✅     |
| Binding a proxy to a session/query_id |    ✅     |
| Random sleep time between clicks      |    ✅     |

### [How to add query id](https://github.com/Freddywhest/RockyRabbitBot/blob/main/AddQueryId.md)

## [Settings](https://github.com/FreddyWhest/PocketFiBot/blob/main/.env-example)

| Settings                   | Description                                                               |
| -------------------------- | ------------------------------------------------------------------------- |
| **API_ID / API_HASH**      | Platform data from which to launch a Telegram session (stock - Android)   |
| **AUTO_MINE**              | Whether the bot should start/claim mining (True / False)                  |
| **SLEEP_BETWEEN_REQUESTS** | Delay between taps in seconds (eg. 70)                                    |
| **USE_PROXY_FROM_FILE**    | Whether to use proxy from the `bot/config/proxies.js` file (True / False) |
| **USE_QUERY_ID**           | Whether to query_id instead of sessions (True / False)                    |

## Installation

You can download [**Repository**](https://github.com/FreddyWhest/PocketFiBot) by cloning it to your system and installing the necessary dependencies:

```shell
~ >>> git clone https://github.com/FreddyWhest/PocketFiBot.git
~ >>> cd PocketFiBot

#Linux and MocOS
~/PocketFiBot >>> chmod +x check_node.sh
~/PocketFiBot >>> ./check_node.sh

OR

~/PocketFiBot >>> npm install
~/PocketFiBot >>> cp .env-example .env
~/PocketFiBot >>> nano .env # Here you must specify your API_ID and API_HASH , the rest is taken by default
~/PocketFiBot >>> node index.js

#Windows
1. Double click on INSTALL.bat in PocketFiBot directory to install the dependencies
2. Double click on START.bat in PocketFiBot directory to start the bot

OR

~/PocketFiBot >>> npm install
~/PocketFiBot >>> cp .env-example .env
~/PocketFiBot >>> # Specify your API_ID and API_HASH, the rest is taken by default
~/PocketFiBot >>> node index.js
```

Also for quick launch you can use arguments, for example:

```shell
~/PocketFiBot >>> node index.js --action=1

OR

~/PocketFiBot >>> node index.js --action=2

#1 - Create session
#2 - Run clicker
```
