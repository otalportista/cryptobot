## 1.0.4 (2021-11-22)


* [❌] -> Remove integration with local api with sepaareted webserver
* [✔️] -> Integrated web server with bot
* [✔️] -> Integration with api in server integred with bot


## 1.0.3 (2021-11-20)



* [✔️] -> Add trend list in coingecko internal module
* [✔️] -> Solved bug on command prefix 
* [✔️] -> Add command to get trend coins
* [✔️] -> Add alert config
* [✔️] -> Add command to create alert
* [✔️] -> Create function when price hits alert user
* [✔️] -> Add command to list all alerts
* [✔️] -> Add command to delete alert
* [✔️] -> Add type of price in command addalert (up/down)
* [✔️] -> Update information in command help
* [✔️] -> Solved bug on alerts
* [✔️] -> Integration with local api to get chart
* [✔️] -> Add command to get chart by symbol ( Only accept coins in system )



## 1.0.2 (2021-11-17)


* [✔️] -> Convert sigla inserted on command addcoin to LowerCase
* [✔️] -> Add 24h % change of coin
* [✔️] -> Organize information in output and add symbol to name
* [✔️] -> Solved the bug to remove the coin and stop the bot as there are more coins
* [❌] -> Remove euro(€) information
* [✔️] -> Add description with informations ( Command for Help )



## 1.0.1 (2021-11-22)


* [✔️] -> Add command to list all coins in system
* [✔️] -> Solved bug in permissions of bot 
* [✔️] -> Pass every commands to file by name ( start.js, stop.js, etc...)
* [✔️] -> Using commands through Command Handler
* [✔️] -> Prevent bot crashes if commands not exists in Command Handler
* [✔️] -> Send message when bot start/stop
* [✔️] -> Add command to change prefix



## 1.0.0 (2021-11-21)


* [✔️] -> Command help add automatic prefix by config
* [✔️] -> Read google sheet and get coin id by sigla and checking on google sheet from coingecko list
* [✔️] -> Change command addcoin only to sigla
* [✔️] -> Solve bug in start/stop 
* [✔️] -> Optmized method to search if exists coins before buy
* [✔️] -> Prevent bot crashes when delete all coins if bot running
* [✔️] -> Prevent start bot if not exists coins
* [✔️] -> Round prices to 3 decimals
* [✔️] -> If exists coins with same symbol give option to user choose one
* [✔️] -> Add timeout to choose coin
* [✔️] -> Delete coin by full name with spaces



## 0.0.3 (2021-11-20)


* [✔️] -> Parse all config from file of type JSON
* [❌] -> Remove coins from array in code 
* [✔️] -> Add coins from file and import
* [✔️] -> Add command to add coin to list
* [✔️] -> Add verification before add coin
* [✔️] -> Add command to remove coin by id
* [✔️] -> Add command help
* [✔️] -> Add uptime to bot
* [✔️] -> Only can execute commands by specific rule
* [✔️] -> Add logs file error
* [✔️] -> Prevent run command if missing arguments



## 0.0.2 (2021-11-19)


* [✔️] -> Command test for return bot permissions
* [✔️] -> Prevent bot crashes when timeout coingecko api
* [✔️] -> Add start channel



## 0.0.1 (2021-11-18)


* [✔️] -> Integration Coingecko Api
* [✔️] -> Integration DiscordJS
* [✔️] -> Automatic prices update
* [✔️] -> Prevent run bot in others channels
* [✔️] -> Prevent run bot in invalid prefix
* [✔️] -> Delete all messsages before bot runs
* [✔️] -> Command start/stop



## Suggestions


* [⌛] -> Add command to get list of exchanges



## Legend


* [❌] -> Removed from bot
* [✔️] -> Added to bot
* [⌛] -> Suggestions to bot