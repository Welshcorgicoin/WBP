Preamble
========
WBP Number: 008

Title: Welshcorgicoin Discord Bot

Author: mocha.btc jolacaleb@gmail.com

Type: Tool Development

Created: 2022-01-11

Discussions-To: https://github.com/welshcorgicoin/WBP

Abstract
========
Develop a discord bot to let `$WELSH` holders know how much `$WELSH` price is.


Milestone
============
- Discord bot which changes its status to its price, in both `$STX` and `$USDT`.
- Add interactive functionality to bot, so bot can listen to some commands with members.

Technical Specifiction
============
- Bot will be written in Python 3.10
- Bot will be dockerized so that anyone can easily deploy and shutdown.

Specification
============
Developer needs to get permission to invite bots in Discord server.

Developer needs a server to place bot.

- Bot will use Arkadiko API and will get the latest price.
- Bot will fetch `STX/WELSH` price for every 2 minutes.
- Bot will fetch `STX/USDT` price for every 2 minutes from Coingecko.
- Calculate the price of `$WELSH`.


$WELSH Bounty
=============
TBD
