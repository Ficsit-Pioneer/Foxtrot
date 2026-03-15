Foxtrot is a Discord bot that runs Ollama capable of running locally on a server/computer for easy usage whenever needed. All you need is a discord bot token! This whole repository serves as a framework for users to add onto.

BEFORE YOU ASK, I MADE THIS WITH GEMINI, BUT I THOUGHT OF EVERY FEATURE. I JUST NEEDED SOMETHING TO CODE IT FOR ME.

Features

-Runs locally (No cost!)
-Scrapes pinned messages of every channel on the current server the bot is on, and the last 500 messages or so on the channel it was summoned to for grabbing the context of the conversation. (This allows for much more accurate results.
-Human/Ollama mode switcher (This means that the bot can be taken over by the person running it using the "/mode" command in the console for pranks and fun!)
-Scrapes the web for accurate results. (Please note the bot may not always be accurate, but I can assure you it works well enough to be considered a good feature.)
-Logs of every message sent in the channel that the bot is in. (Due to recent versions, Gemini may have omitted this feature from the code, so this may not exist. I haven't had a super popular server to test it in.)
-The ability to summon the bot to a certain channel in a certain server. (This means tagging @Foxtrot or talking about "Foxtrot" in a message means the bot will immediately be summoned to you.)
-Emergency exit capability. (This means if the user denoted as the admin for the bot says a certain phrase, the bot will immediately turn off. This is great for conversations that may involve sensitive content or info you don't want the bot to see. Please note this turns off EVERY instance of YOUR bot.)
-And more that I forgot about!

Please note that every mention of Foxtrot or @Foxtrot listed above will be replaced with your own bot's name. This is the name you give to it in the Discord Developer Application.

Installation:

Python 3.10+ should do the trick. (opt for 3.12)

pip install 
