# DiscordBot_GameStatus

Modification-modifications of the module https://github.com/Ramzi-Sah/game-status-discordbot-selfhosted

Thanks to Ramzi-Sah and soulkobk for their work

The difference in this version:
- Removed the bat file for running under windows to save space on the hosting
- Updated the used libraries (as of October 2024)
- Removed the unused and non-functioning functionality of building an online graph

Recommendation:
Set up 1 monitoring per project clone
The operation is still unstable and if there is no response from the monitored server for a long time, one of the threads ends, to restart it, a complete restart of the bot will be required

##How to install?

1. clone project
2. cd US66_DiscordBot_GameStatus
3. npm install
4. nano config.json
5. node index.js&
