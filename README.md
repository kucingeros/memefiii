
## TomarketBot
🖱️ clicker for [https://t.me/memefi_coin_bot](https://t.me/memefi_coin_bot/main?startapp=r_edaef4ea1a)


## Functionality
| Functional                                                     | Supported |
| -------------------------------------------------------------- | :-------: |
| Purchasing TapBot                                              |    ✅     |
| Starting TapBot                                                |    ✅     |
| Claiming TapBot reward every 3 hours                           |    ✅     |
| Claiming Daily Combo                                           |    ✅     |
| Spinning game                                                  |    ✅     |
| User Agent for each session                                    |    ✅     |
| Multithreading                                                 |    ✅     |
| Binding a proxy to a session                                   |    ✅     |
| Auto-purchase of items if you have coins (tap, energy, charge) |    ✅     |
| Random sleep time between clicks                               |    ✅     |
| Random number of clicks per request                            |    ✅     |
| Support tdata / pyrogram .session / telethon .session          |    ✅     |
| Referral bonus claiming after first time registering           |    ✅     |

## Warning !
According to [Telegram TOS](https://core.telegram.org/api/obtaining_api_id#using-the-api-id) all accounts that sign up or log in using unofficial Telegram API clients are automatically put under observation to avoid violations of the Terms of Service.

So be careful, hopefully your account won't get banned.

# Use Python 3.11 or less

## Settings data file
| Settings                                      | Description                                                                            |
| --------------------------------------------- | -------------------------------------------------------------------------------------- |
| **API_ID / API_HASH**                         | Platform data from which to launch a Telegram session (stock - Android)                |
| **MIN_AVAILABLE_ENERGY**                      | Minimum amount of available energy, upon reaching which there will be a delay (eg 100) |
| **SLEEP_BY_MIN_ENERGY**                       | Delay when reaching minimum energy in seconds (eg 200)                                 |
| **ADD_TAPS_ON_TURBO**                         | How many taps will be added when turbo is activated (eg 2500)                          |
| **AUTO_UPGRADE_TAP**                          | Should I improve the tap (True / False)                                                |
| **MAX_TAP_LEVEL**                             | Maximum level of tap pumping (eg 5)                                                    |
| **AUTO_UPGRADE_ENERGY**                       | Should I improve the tap (True / False)                                                |
| **MAX_ENERGY_LEVEL**                          | Maximum level of tap pumping (eg 5)                                                    |
| **AUTO_UPGRADE_CHARGE**                       | Should I improve the tap (True / False)                                                |
| **MAX_CHARGE_LEVEL**                          | Maximum level of tap pumping (eg 5)                                                    |
| **APPLY_DAILY_ENERGY**                        | Whether to use the daily free energy boost (True / False)                              |
| **APPLY_DAILY_TURBO**                         | Whether to use the daily free turbo boost (True / False)                               |
| **RANDOM_TAPS_COUNT**                       | Random number of taps (eg 50,200)                                                      |
| **SLEEP_BETWEEN_TAP**                         | Random delay between taps in seconds (eg 10,25)                                        |
| **USE_PROXY_FROM_FILE**                       | Whether to use proxy from the `bot/config/proxies.txt` file (True / False)             |
| **SLEEP_BETWEEN_TAP**                         | Random delay between taps in seconds (eg 10,26)                                        |
| **AUTO_BUY_TAPBOT**                           | Whether to purchase tapbot automatically (True / False)                                |
| **AUTO_SPIN**                                 | Whether to spin automatically (True / False)                                           |
| **AUTO_GENERATE_USER_AGENT_FOR_EACH_SESSION** | Whether you want to generate user agent for each session (True / False)                |

## Requirements
- Python 3.9 (you can install it [here](https://www.python.org/downloads/release/python-390/))
- Telegram API_ID and API_HASH (you can get them [here](https://my.telegram.org/auth))
  
## Obtaining API Keys
1. Go to my.telegram.org and log in using your phone number.
2. Select "API development tools" and fill out the form to register a new application.
3. Record the API_ID and API_HASH provided after registering your application in the .env file.

## Clone this repository

	git clone https://github.com/kucingeros/memefiii

## goto tomarket directory

	cd memefiii
 
## install the require library
1. Install the required dependencies:
  
   ```bash
   python -m pip install -r requirements.txt
   ```
2. Please edit the name file .env-example to .env and add your API_ID and API_HASH:

## Edit data.txt, input you data token in data.txt, find you token in How to Find Account Token. One line for one data account, if you want add you second account add in new line!

## execute the main program
1. Run the bot:
   ```bash
   .\START.bat
   ```
2. Select Number
3. Type "1" without quotation marks, for create session
4. If you done create the session
5. next, Run the bot:
   ```bash
   .\START.bat
   ```
6. Type "2" without quotation marks, for run the bot
