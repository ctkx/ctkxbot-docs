# .mod

[Back home](../index.md)

### Setup

The `.mod` commands require some setup which can only be complete by the [Server/Guild Owner](/guild_setup/index.md)


### Alert words

The alertwords function allows you to have the bot watch for when certain words are posted. 
There are 3 types of triggers:

| Trigger  | Outcome |
|----------|---------|
| `silent` | The message that triggered the alert is silently logged to the logging room.<br>No warning is issued and the user does not know about the alert. | 
| `warn` | The message that triggered the alert is logged to the logging room.<br>The message is responded to with a public warning, If the user gets enough warnings, they are banned |
| `ban` | The message that triggered the alert is logged to the logging room.<br>The message is responded to with a public warning, And the user is banned |

You can `add` , `remove` , or `list` alert words:

| Command      | Additional Input | Output                 |
|--------------|------------------|------------------------|
| `.mod` | `add` `silent` `alertword` `alertword=TriggerWord`   | Adds "TriggerWord" as a silent trigger. |
| `.mod` | `remove` `ban` `alertword` `alertword=TriggerWord`   | Removes "TriggerWord" as a ban trigger. |
| `.mod` | `list` `warn` `alertword`  | Lists alertwords with warn trigger. |



