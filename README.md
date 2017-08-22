Discord Webhooks Wrapper for PHP
====

A lightweight wrapper to interact with [Discord](https://discordapp.com) webhooks.

### Getting Started
No dependencies. Just clone and use.

### But first, setting up a webhook in Discord
*This currently only works in Discord's public test build, which can be found [here for Windows](https://discordapp.com/api/download/ptb?platform=win) and [here for Mac](https://discordapp.com/api/download/ptb?platform=osx).*

1. On a server you own (or have the "Manage Webhooks" permission on), open Server Settings, and select 'Webhooks' on the menu: ![Step 2](http://i.imgur.com/jovnbVO.png)

2. Click the "Create Webhook" button and complete the form. The "Name" field and avatar that you set are the defaults, and may be overriden in this wrapper, but ***the channel you pick cannot be changed by the wrapper.*** You'll need a separate URL for each channel you want to post to. ![Step 2](http://i.imgur.com/u8CcmE6.png)

3. Copy the "Webhook URL" into the ```$APP_URI``` variable in ```log.php``` 

### Using Command-Line 
```bash
php log.php "My message here"
```

### Copyright

Nothing hard there, [Arianna Story](https://github.com/AuroraAri/Discord-Webhooks-PHP) creates a beautiful library, I only simplify using it.

