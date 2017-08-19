# Dokku Telegram

Dokku Slack is a plugin for [Dokku](https://github.com/progrium/dokku) that notifies [Telegram](https://telegram.org/) of deployments.

## Installation

```sh
# dokku 0.3.26
$ git clone https://github.com/m0rth1um/dokku-telegram /var/lib/dokku/plugins/telegram

# dokku 0.4+
$ dokku plugin:install https://github.com/m0rth1um/dokku-telegram.git
```

## Commands

```sh
$ dokku help
    telegram:clear_chat_id [app]           Clears Telegram token
    telegram:clear_token [app]             Clears Telegram token
    telegram:get [app]                     Display Telegram data
    telegram:set_chat_id [app] <chat_id>   Set chat ID
    telegram:set_token [app] <token>       Set Telegram BotAPI token
```