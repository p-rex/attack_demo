# Getting events via Streaming API
This script gets Falcon events via Streaming API and save them to a local file.

# Usage
1. Create an API key in Falcon console. Scope: `Event streams: Read`
1. Download `config.env`. You may change the filename.
1. Modify config.env.
1. Execute the following commands.　If you have changed the filename of the `config.env`, change the `config.env` part of the commands.
```shell
curl -sSL https://raw.githubusercontent.com/p-rex/warehouse/main/CS_Script/StreamingAPI/getEvents.sh | bash -s config.env
```

# Notes
This script does not support refreshing session. Therefore, streaming will end after 30 minutes.
