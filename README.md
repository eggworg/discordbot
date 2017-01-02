# Discord Bot v1.0 

This Discord Bot is written in <Link href="https://www.jetbrains.com/idea/" target="_blank">Java</Link>, utilizing the [Discord4J](https://github.com/austinv11/Discord4J) API, and is inspired by SexualRhinoceros' [MusicBot](https://github.com/Just-Some-Bots/MusicBot)<br>

### Setting up

If you do not have a bot application created yet, click [here](https://discordapp.com/developers/applications) and create a new application. The `app name` will be your bot's username. The `app icon` will be your bot's icon. Don't add any URIs. App description can be left empty. For example:

![application](https://cloud.githubusercontent.com/assets/24867967/21583888/a5a410fe-d061-11e6-9a18-5b7a7293b88e.png?raw=true)

After you've created your application, click `Create a Bot User`.

![bot user](https://cloud.githubusercontent.com/assets/24867967/21583922/ac315b60-d062-11e6-9057-55b22f08b93e.png?raw=true)

You should now see this:

![app bot user](https://cloud.githubusercontent.com/assets/24867967/21583936/4b8c4b16-d063-11e6-9411-6c51ebc9ece7.png?raw=true)

Click the `click to reveal` button in text and copy the token. You will need this to authenticate your bot to the discord servers.

### Editing Settings.ini

If you don't have Java installed yet, click [here](https://java.com/en/download/) to download the latest available version.

If your OS is Windows, please don't use notepad! Instead, consider downloading a dedicated text editor with .ini supported syntax highlighting such as [Notepad++](https://notepad-plus-plus.org/).

`;` are comments. They're here to assist you through the settings file. After you finish editing `Settings.ini`, it's time to run the bot.

### Starting the bot

Before you actually run the bot, you will need to add the bot user to your discord server.<br>
You will need to go back to your bot application and retrieve the client id.

![client id](https://cloud.githubusercontent.com/assets/24867967/21594342/7c558b22-d0ef-11e6-8cf6-e913c1ba7695.png?raw=true)

Next, you'll need to copy the link below and replace `CLIENT_ID` with your client id.
https://discordapp.com/api/oauth2/authorize?client_id=CLIENT_ID&scope=bot&permissions=0

You should see a screen similar to this:

![add to server](https://cloud.githubusercontent.com/assets/24867967/21594394/0f99cdda-d0f0-11e6-97b2-58521a8ced5f.png?raw=true)

Choose your server and click `Authorize`. Note: You must have the `Manager Server` permission on your server.

Now that we're finished adding the bot to the server, we'll need to run it.

If you're on windows, double click on `run.bat`. 

If you're on linux, you will need to give execute permission to `run.sh`.<br>
To do this, open up terminal and change to your bot's directory. You will then need to type `chmod +x ./run.sh`, which lets you run the script. Now simply type `./run.sh` to start the bot.

If successful, your bot should now be online. Have fun! :)
