# java-discord-bot

A very simple discord bot written in java

## To use this bot, you will need to follow these steps:

1.) Create a Discord bot and get its token from the Discord Developer Portal.
2.) Make sure you have Java and the JDA library installed on your machine.
3.) Copy the code of the bot and save it to a file named "MyBot.java".
4.) Edit the code and replace "your-bot-token-here" with your bot's token, and "your-openweathermap-api-key-here" with your OpenWeatherMap API key.
5.) Open a command prompt or terminal and navigate to the directory where you saved the "MyBot.java" file.
6.) Compile the bot by running the command "javac -cp ".;path/to/jda.jar" MyBot.java" (replace "path/to/jda.jar" with the path to the JDA library on your machine).
7.) Run the bot by running the command "java -cp ".;path/to/jda.jar" MyBot" (again, replace "path/to/jda.jar" with the path to the JDA library on your machine).

Once the bot is running, you can use it in your Discord server by typing commands in the channel where the bot is present.

## The available features/commands are:

**!hello** - responds with a greeting and mentions the user who sent the command.
**!ping** - responds with "Pong!" and the response time in milliseconds.
**!weather location** - looks up the current weather for the specified location and prints it in the channel where the command was sent.
**custom commands** - if you have defined custom commands in a file named "commands.txt", you can use them by typing the command name in the channel where the bot is present.

