# Basic bot setup

## Greet Messages
Greet messages are enabled by default. You can modify message settings by using the `bb greet` command. 
> Use `bb vars` to see all available variables you can use in message or add-on message.
> Below is a picture reference for sections used in setting up greet messages.
![Reference for section](https://cdn.discordapp.com/attachments/782443597122502707/993897637042466897/unknown.png)

- **Message :** 
	- `bb greet message <Thank You {user} for the boost <3>` - sets greet message to "Thank You {user} for the boost <3"
		> You can set up to 3 greet messages with the non-premium version of the bot. With premium, you can set up to 10 greet messages!
		
	- `bb greet message disable` - removes all greet messages.
		> You can't edit/remove specific greet messages
	
	- `bb greet addon <Hello {user}>` - sends an add-on message along with embed (only if embed is enabled). 
		> You can use this to ping the user and/or any role you want

- **Footer :**
	- `bb greet footer <Thank you so much for boosting~>` - sets footer text to "Thank you so much for boosting~"
		> Emojis don't work here.
	- `bb greet footer-icon <user|server|URL|disable>`
		> `bb greet footer-icon user` sets footer icon as booster's profile pic 
		> `bb greet footer-icon server` sets footer icon as server icon 
		> `bb greet footer-icon https://cdn.discordapp.com/emojis/803182075666366494.gif` sets footer icon as the custom URL (default)
		> `bb greet footer-icon disable` removes footer icon 

- **Author :**
	- `bb greet author <{user}>` - sets author text to "{user}"
	- `bb greet author icon <user|server|URL|disable>`
		> `bb greet author-icon user` sets author icon as booster's profile pic 
		> `bb greet author-icon server` sets author icon as server icon 
		> `bb greet author-icon https://i.imgur.com/X0CBc8U.gif` sets author icon as the custom URL (default)
		> `bb greet author-icon disable` removes author icon

- **Channel :** 
	- `bb greet channel <#boosts>` - sends greet message in #boosts channel. 
	- `bb greet dm <enable|disable>` - DMs the booster and will not post greet message in the channel, if enabled. 
		> Disable option makes bot send the greet message in the channel

- **Image or Thumbnail :** 
	> Works only if embed is enabled (enabled by default) 
	
	- `bb greet thumbnail <user | server | URL | disable>` - works respectively.
		> `user` will show booster's profile pic in thumbnail (Default)
		> `server` will show server's icon in thumbnail
		> `URL` will show the picture/gif you chose
		
	- `bb greet image <URL | disable>` - can set any URL you prefer.
		> Disabled by default
		
- **Stats & Embed :**
 Both are enabled by default.
	 - `bb greet stats <enable | disable>` - shows current boosts and level achieved on boost, if any. 
	 - `bb greet embed <enable | disable>` - send message as embed, if enabled. 

- **Reactions :**
	- `bb greet emoji <emoji | disable>` - sets emoji for auto reaction on default boost message. 
	- `bb greet react <default|custom|both>` - sets which message you want the reaction to be on.
		> default - default system message (default) 
		> custom - bot's custom greet message (if enabled) 
		> both - on both messages

- **Test :**
	- `bb greet test` - sends greet message into the set channel with all your settings.
  
**NOTE :** Make sure [_System Messages on server boosts_](https://just-sleeping.with-your.mom/ApplicationFrameHost_hCRI6wkzJJ.png) are **enabled** and bot has permissions in system channel.
