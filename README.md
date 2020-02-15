# Football2Twitch

A chat bot that posts live football fixtures to Twitch, ideal to improve engagement.


## Status

This is a bot I am currently using on my Twitch channel ([ilpeggioretv](https://www.twitch.tv/ilpeggioretv)): as long as I use it it will be actively maintained.

## Description

The script retrieves live football results via API using [API-FOOTBALL](https://www.api-football.com/documentation) and post them to Twitch.

To make it work, before running it, you will need to define certain variables in the config file.

Required API-FOOTBALL parameters (get yours from [rapidapi.com](http://rapidapi.com/)):

- Football API Host
- Football API Key
- Football API Fixture URL

Additional information are needed to let the chat bot connect to Twitch and join the desired channel. 

These variables should also be defined in the config file:

- Twitch Host
- Twitch Port
- Twitch Username (of the bot)
- Twitch Password
- Twitch Channel

It is recommended to set the bot as Moderator.

## Final comments

If you found this chat bot helpful show some ♥ by following [my Twitch channel](https://www.twitch.tv/ilpeggioretv) :-)
