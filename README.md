Installation:
$ git clone https://github.com/catskittens/triviabot.git

$ cd triviabot/

$ cp config.example.json config.json

$ python bot.py

```json
{
	
	"server": "irc.myserver.com",
	"port": 6667,
	"nickname": "Test",
	"password": "",
	"account": "",
	"channel": "#Test",
	"admins": ["admin"],
	"prefix": "!",

	"--OPTIONAL CONFIGURATION--": "--You don't have to edit anything below here, but you can if you so wish.--",
	"enabledtopics": ["topic", "topic", "topic"],
	"savepoints": false
}
