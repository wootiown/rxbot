## RXBot

RXBot is a songrequest bot for Twitch using Google Play Music, originally created for the Twitch channel [RXBots](https://www.twitch.tv/rxbots).

⚠️ This project is still in early development and may not function as expected ⚠️

-----

### Dependencies

Python 2.7.9 is required, earlier versions of 2.7 may have issues. Download here: https://www.python.org/downloads/release/python-279/

Install dependencies by running `Install_Requirements.bat` or by using  `pip install -r requirements.txt` in the bot's directory.

VLC Media Player must also be installed, but does not have to be running. Download here: https://www.videolan.org/vlc/index.html

-----

### Commands

- `!sr (or !songrequest)` Makes a song request. May be a search query for a song, a youtube link, or a link to an audio file online.

- `!pause` Pauses the music

- `!play` Plays the music

- `!veto` Skips to the next song

- `!wrongsong (#)` Removes the last request from the queue, or the specified ID. May only modify your own requests.

- `!nowplaying` Shows the current playing song. This will read exactly what is in nowplaying.txt

- `!volume `, `!volumeup` & `!volumedown` [MOD] Control the volume. May specify a value for more specific adjustments.

- `!clearqueue` [MOD] Clears the song queue

- `!clearsong` [MOD] - Functionally identical to wrongsong, but may target any user's requests.

- `!addsong` [MOD] Functionally identical to sr, but adds songs to the backup playlist rather than the queue.
-----

### Get in touch

Join us in the #therxbot-dev channel in the [RXBots Discord chat](https://discord.gg/3gagd4Y).
