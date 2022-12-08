# Discord YAGPDB Custom Flair Command

Desc: Custom bot commands designed for YAGPDB Discord bot for adding customizable flairs based on the user's requirement.


## Source code

[Source Code](https://github.com/ne3lakolkar/YAGPDB-Custom-Command-Nickname-Flair/blob/main/Command%20Source%20Code) contains the command code and the expected response. 


# Implementation

*System Input* : -flair GER

*System Response* : [GER] ne3lakolkar

For Example:

![response](https://github.com/ne3lakolkar/YAGPDB-Custom-Command-Nickname-Flair/blob/main/Resources/Screenshot%202022-12-08%20123032.png)


## Exception Handling

Some exceptions and errors that can be taken care by caution/error message returned by the bot. 
For example:

![response](https://github.com/ne3lakolkar/YAGPDB-Custom-Command-Nickname-Flair/blob/main/Resources/Screenshot%202022-12-08%20122957.png)

## Known errors and mishaps

- Missing permissions - The bot must have higher authorization permissions to change the user's nickname. In some cases permissions need to be overridden by users. 
For example: Moderators and Admins. 

![response](https://github.com/ne3lakolkar/YAGPDB-Custom-Command-Nickname-Flair/blob/01c8e40729dfdf5e1333ec9a9e797ea22294e139/Resources/Screenshot%202022-12-08%20122613.png)
- Username/nickname length - Discord supports usernames upto 27 characters. Make sure that the flair and the username fits within the range provided. You may return a custom exception response as: 

![response](https://github.com/ne3lakolkar/YAGPDB-Custom-Command-Nickname-Flair/blob/main/Resources/Screenshot%202022-12-08%20124827.png)
- Case Sensitivity - The commands are case sensitive so the spelling mistakes are NOT taken care of. 

![response](https://github.com/ne3lakolkar/YAGPDB-Custom-Command-Nickname-Flair/blob/main/Resources/Screenshot%202022-12-08%20122844.png)
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

## Misc.
I personally developed this project for Chelsea Football Club Official Discord Server Community. National Football is on horizon and members from the same club now start supporting their favourite countries. To classify and make the engagement among these international football rivals, flairs was introduced. 
It was implemented just before the tournament started. Hence the bot command notched a huge response.

Feel free to join the community on discord by https://discord.gg/chelseafc
 
![response](https://github.com/ne3lakolkar/YAGPDB-Custom-Command-Nickname-Flair/blob/01c8e40729dfdf5e1333ec9a9e797ea22294e139/Resources/Screenshot%202022-12-08%20123116.png)
