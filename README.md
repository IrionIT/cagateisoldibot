# CagateISoldiBot
Telegram bot to manage Netflix's shared account with your friends and family.

_(In english 'cagate i soldi' is something like 'give me your money')_

## Installation:
```bash
    $ virtualenv -p python3 venv #(optional)
    $ source venv/bin/activate #(optional)
    $ pip3 install -r requirements.txt
    $ sed 's/INSERT_TOKEN_HERE/YOUR_TOKEN/' -i Settings.py
    $ python3 CreateDB.py
    $ python3 Main.py
```
**Replace YOUR_TOKEN with bot's token given by BotFather**

### Demo
[![asciicast](https://asciinema.org/a/215057.svg)](https://asciinema.org/a/215057)


## TODO
- [x] Notify member when payment is confimed by admin // check
- [ ] Notify admin if bot removed from a group

## Try it here!
It's still in beta and can stop working/lose data without warning, but you can give a try: [http://t.me/cagateisoldibot](http://t.me/cagateisoldibot) 
