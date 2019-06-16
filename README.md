# CagateISoldiBot
Telegram bot to manage Netflix's shared account with your friends and family.

_(In english 'cagate i soldi' is something like 'give me your money')_

## Installation:
[![asciicast](https://asciinema.org/a/215057.svg)](https://asciinema.org/a/215057)
```bash
    $ virtualenv -p python3 venv #(optional)
    $ source venv/bin/activate #(optional)
    $ pip3 install -r requirements.txt
    $ sed 's/INSERT_TOKEN_HERE/YOUR_TOKEN/' -i src/Settings.py
    $ python3 CreateDB.py
    $ python3 Main.py
```
Obviously replace _YOUR\_TOKEN_ with bot's token given by BotFather.

## TODO
- [x] Notify member when payment is confimed by admin;
- [ ] Notify admin if bot removed from a group;
- [ ] Write tests;

## Try it here!
It's still in beta and can stop working/lose data without warning, but you can give a try: [http://t.me/cagateisoldibot](http://t.me/cagateisoldibot) 
