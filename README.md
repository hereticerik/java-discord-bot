# java-discord-bot

A very simple discord bot written in java<br>

## To use this bot, you will need to follow these steps:<br><br>

1.) Create a Discord bot and get its token from the Discord Developer Portal.<br>
2.) Make sure you have Java and the JDA library installed on your machine.<br>
3.) Copy the code of the bot and save it to a file named "MyBot.java".<br>
4.) Edit the code and replace "your-bot-token-here" with your bot's token, and "your-openweathermap-api-key-here" with your OpenWeatherMap API key.<br>
5.) Open a command prompt or terminal and navigate to the directory where you saved the "MyBot.java" file.<br>
6.) Compile the bot by running the command "javac -cp ".;path/to/jda.jar" MyBot.java" (replace "path/to/jda.jar" with the path to the JDA library on your machine).<br>
7.) Run the bot by running the command "java -cp ".;path/to/jda.jar" MyBot" (again, replace "path/to/jda.jar" with the path to the JDA library on your machine).<br>
<br>
Once the bot is running, you can use it in your Discord server by typing commands in the channel where the bot is present.<br>

## The available features/commands are:<br><br>

**!hello** - responds with a greeting and mentions the user who sent the command.<br>
**!ping** - responds with "Pong!" and the response time in milliseconds.<br>
**!weather location** - looks up the current weather for the specified location and prints it in the channel where the command was sent.<br>
**custom commands** - if you have defined custom commands in a file named "commands.txt", you can use them by typing the command name in the channel where the bot is present.<br>

You can easily create your own custom commands using text files.


**This Discord Bot was made for Educational Purposes as an Example**
