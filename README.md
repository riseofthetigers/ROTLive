# This Score board is borrowed from uditha-madusanka's repo.

# Cricinfo with Conky
Crickinfo with Conky dashboard (Live score + Full scroreboard)

This widget can be used to view live score on a particular match you interested.

1. 	Find the match ID (ESPN Crickinfo) you want to watch the score using "MatchIDFinder.sh"
Eg: `MatchIDFinder.sh Australia`
This will list down all live matches payed by Australian team

2. 	Then copy the match ID and update the "conkyrc" file
`${font}${color2}${execi 30  bash scoreboard.sh <match ID>}`

Enjoy live cricket scores

![cricinfo_conky](https://github.com/uditha-madusanka/conky_crickinfo/blob/master/crickinfo.png)
