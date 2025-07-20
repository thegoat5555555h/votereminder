# VoteReminder Minecraft Plugin

A simple Minecraft plugin that reminds players to vote for your server.

## Features

- Sends a reminder message to players to vote.
- Configurable vote URL and reminder message.

## Installation

1. Download the latest `VoteReminder.jar` from the [releases](./releases) or build it from source.
2. Place `VoteReminder.jar` in your server's `plugins` folder.
3. Restart or reload your Minecraft server.

## Configuration

After running the server with the plugin once, a `config.yml` will be generated in the `plugins/VoteReminder/` directory. You can edit it as follows:

```yaml
vote-url: "https://yourserver.com/vote"
reminder-message: "&aDon't forget to vote! Use &b/vote &ato get the link."
```

- **vote-url:** The URL where players can vote for your server.
- **reminder-message:** The message shown to players. Minecraft color codes (e.g., `&a`, `&b`) are supported.

## Commands

- `/vote`  
  Sends the vote URL to the player.

## Building from Source

1. Clone this repository.
2. Import the project into your Java IDE.
3. Build the project with your preferred tool (Maven/Gradle/IDE).
4. The compiled `VoteReminder.jar` will be in the `target` or `build/libs` directory.

## License

MIT 
