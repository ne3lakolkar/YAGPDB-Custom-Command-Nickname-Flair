# Discord YAGPDB Custom Flair Command

Desc: Custom bot commands designed for YAGPDB Discord bot for adding customizable flairs based on the user's requirement.


## Source code

Source code contains the command code and the expected response. 


# Implementation

*System Input* : -flair GER
*System Response* : [GER] ne3lakolkar


## Known errors and mishaps

- Missing permissions - The bot must have higher authorization permissions to change the user's nickname. In some cases permissions need to be overridden by users. 
For example: Moderators and Admins. 
- Username/nickname length - Discord supports usernames upto 27 characters. Make sure that the flair and the username fits within the range provided.
- Case Sensitive - The commands are case sensitive so the spelling mistakes are NOT taken care of. 

> **Note:** You cannot manipulate bot permissions from YAGPDB Dashboard. Must change the settings in the discord role options and permissions. 


## Examples

Here are some of the examples how you can use the bot. Currently I've demonstrated the purpose of fulfilling the National Football team's flairs and also F1 Constructors flairs. Can also be implemented to classify moderators and admins from rest of the users. 

|                |Input                          |Response|
|----------------|-------------------------------|-----------------------------|
|Germany National Football Team flair|`'-flair ger'`            |*updates username to* '[GER] username'            |
|F1 Mercedes Constructors' flair|`'-flair merc'`            |    *updates username to* '[MERC] username'        |
|Moderator/Admin flair          |`'-flair mod'`|*updates username to* '[MOD] username'|

## Conclusion

Head over to YAGPDB Bot console and try it out yourself!

Thank you.
