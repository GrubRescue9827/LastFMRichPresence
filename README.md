# LastFMRichPresence BetterDiscord Plugin
This plugin allows you to show what you're listening via Last.fm. You can set it up for Soundcloud, Youtube Music and lot of other sites, not just Spotify (with [Webscrobbler](https://chrome.google.com/webstore/detail/web-scrobbler/hhinaapppaileiechjoiifaancjggfjm?hl=en)). 
~~Keep in mind that you can't click your own rich presence buttons. Other people can.~~ (Works fine for me?)

## Note:
This is a fork that makes the RPC a little prettier (As shown)

![Screenshot](https://i.imgur.com/LoLOtrr.png)

I'm NOT a programmer, I've just hacked this together through trial and error. This is mostly for my personal use, but I might as well post it incase anyone wants something similar.
I've tried to document everything I could understand in the JS file, hopefully it makes it easier for anyone who doesn't know JavaScript (like me) to edit.
I'll hopefully add some more customization options so you don't have to edit the js file directly. But that's work for future me to deal with.

## Features
* Show what music you're listening with Last.fm. With [Webscrobbler](https://chrome.google.com/webstore/detail/web-scrobbler/hhinaapppaileiechjoiifaancjggfjm?hl=en) you can show music from 280+ different websites (see list [here](https://web-scrobbler.com/)).  
* Hide Last.fm Rich Presence when listening from Spotify (optional setting).  
* Shows 'Listen on YouTube' button when can find YouTube link.  
* You can also set up 'Listen on Soundcloud' button if you set Soundcloud Authorization key.  
* Easy setup. You can show scrobbles of any person.  

## Installation
* Download [this](https://raw.githubusercontent.com/GrubRescue9827/LastFMRichPresence/main/LastFMRichPresence.plugin.js) file and put it in BetterDiscord plugin folder.  
* Go to [Last.fm API](https://www.last.fm/api) and create API key (it only takes few minutes, write anything about app, dont need to provide callback or website).
* If you accidently forget your API key, you can find it [here](https://www.last.fm/api/accounts)
* Put Last.fm key and your Last.fm username in plugin settings.  
* Wait a minute and it should start working  
* If it doesn't, make sure you have this option on:  
![turn this on](https://media.discordapp.net/attachments/994325698397356203/994331512709324891/unknown.png)  

![Option menu](https://lune.dimden.dev/e88741e140.png)  

## Getting Soundcloud Authorization key
You can get OAuth key by having Soundcloud app (but they stopped giving access) or by going to [any search page](https://soundcloud.com/search?q=test), opening DevTools Network tab and finding `search?` request and copying `Authorization` header (you have to be logged in & it doesn't matter if you include `OAuth ` part or not).  

![Soundcloud](https://lune.dimden.dev/d037357515.png)  
![Soundcloud2](https://lune.dimden.dev/56a2a124b5.png)  

## Will I get banned for using this?
This plugin uses RPC, which is official API used by lot of programs. It doesn't update your status and won't count as selfbotting.  

## Support
You're on your own, bud. Sowwy, idk what I'm doing! >w< 

## License
MIT
