## Version 0.0.1
[✔️] -> Integration Coingecko Api\
[✔️] -> Integration DiscordJS\
[✔️] -> Automatic prices update\
[✔️] -> Prevent run bot in others channels\
[✔️] -> Prevent run bot in invalid prefix\
[✔️] -> Delete all messsages before bot runs\
[✔️] -> Command start/stop

## Version 0.0.2
[✔️] -> Command test for return bot permissions\
[✔️] -> Prevent bot crashes when timeout coingecko api\
[✔️] -> Add start channel

## Version 0.0.3
[✔️] -> Parse all config from file of type JSON\
[❌] -> Remove coins from array in code \
[✔️] -> Add coins from file and import\
[✔️] -> Add command to add coin to list\
[✔️] -> Add verification before add coin\
[✔️] -> Add command to remove coin by id\
[✔️] -> Add command help\
[✔️] -> Add uptime to bot\
[✔️] -> Only can execute commands by specific rule\
[✔️] -> Add logs file error\
[✔️] -> Prevent run command if missing arguments

## Version 1.0.0
[✔️] -> Command help add automatic prefix by config\
[✔️] -> Read google sheet and get coin id by sigla and checking on google sheet from coingecko list\
[✔️] -> Change command addcoin only to sigla\
[✔️] -> Solve bug in start/stop \
[✔️] -> Optmized method to search if exists coins before buy\
[✔️] -> Prevent bot crashes when delete all coins if bot running\
[✔️] -> Prevent start bot if not exists coins\
[✔️] -> Round prices to 3 decimals\
[✔️] -> If exists coins with same symbol give option to user choose one\
[✔️] -> Add timeout to choose coin\
[✔️] -> Delete coin by full name with spaces

## Version 1.0.1
[✔️] -> Add command to list all coins in system\
[✔️] -> Solved bug in permissions of bot \
[✔️] -> Pass every commands to file by name ( start.js, stop.js, etc...)\
[✔️] -> Using commands through Command Handler\
[✔️] -> Prevent bot crashes if commands not exists in Command Handler\
[✔️] -> Send message when bot start/stop\
[✔️] -> Add command to change prefix

## Version 1.0.2
[✔️] -> Convert sigla inserted on command addcoin to LowerCase\
[✔️] -> Add 24h % change of coin\
[✔️] -> Organize information in output and add symbol to name\
[✔️] -> Solved the bug to remove the coin and stop the bot as there are more coins\
[❌] -> Remove euro(€) information\
[✔️] -> Add description with informations ( Command for Help )

## Version 1.0.3
[✔️] -> Add trend list in coingecko internal module\
[✔️] -> Solved bug on command prefix \
[✔️] -> Add command to get trend coins\
[✔️] -> Add alert config\
[✔️] -> Add command to create alert\
[✔️] -> Create function when price hits alert user\
[✔️] -> Add command to list all alerts\
[✔️] -> Add command to delete alert\
[✔️] -> Add type of price in command addalert
        

## Usage
For example prefix are equal to **!**
#### To start bot
>!start

## Suggestions
[⌛] -> Add command to get list of exchanges\
[⌛] -> Get charts from tradingview

## Legend
[❌] -> Removed from bot\
[✔️] -> Added to bot\
[⌛] -> Suggestions to bot

## Requirements
-> Discord.JS                  ( Version: 13.3.1 )\
-> Coingecko-API               ( Version: 1.0.10 )\
-> Public Google Sheets Parser ( Version: 1.2.6  )

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.\
Please make sure to update tests as appropriate.

## License
[MIT](https://choosealicense.com/licenses/mit/)

