# Cryptocurrency bot by OTalPortista & C0ffeeL0ver

## 🌟 Features
- Configure coin list
- Update crypto prices every x seconds
- Alerts when coin hit certain price
- Giving chart of certain coin

## 🆕 Updates
You can check all updates of bot clicking [here](https://github.com/otalportista/cryptobot/blob/main/CHANGELOG.md)

## 🚀 Usage
For example prefix are equal to **!**
* To start bot

`!start`

* To stop bot

`!stop`

* To list all coins in system

`!coinlist`

* To get price of specific coin

`!coin <symbol>`

* To add coin

`!add <symbol>`

* To delete coin

`!delcoin <coin name>`
> To get coin name you need to list all coins

* To list all alerts

`!alertlist <user>`
>user is optional, only required if you want to list alerts of specific user

* To add alert

`!addalert <up/down> <symbol> <price>`
>Up - If current price is lower or equal than price of alert<br>
>Down - If current price is higher or equal than price of alert

* To delete alert

`!delalert <id>`
> To get id you need to list all alerts

* To get chart

`!chart <symbol> <timestamp>`
>Timestamps - 1m 3m 5m 15m 30m 45m 1h 2h 3h 4h 1d 1w

* To change prefix

`!prefix <new prefix>`

* To get current version

`!version`



## Requirements

* Discord.JS                  ( Version: 13.3.1 )
* Coingecko-API               ( Version: 1.0.10 )
* Public Google Sheets Parser ( Version: 1.2.6  )


## 🤝 Contributing
Contributions, issues and feature requests are welcome.<br />
Feel free to check [issues page](https://github.com/otalportista/cryptobot/issues) if you want to contribute.<br />

## 📝 License
Cryptobot is licensed under the [MIT license](https://github.com/otalportista/cryptobot/blob/main/LICENSE).<br />
This is not an official Discord product. It is not affiliated with nor endorsed by Discord Inc.<br />

© 2021 OTalPortista & C0ffeeL0ver