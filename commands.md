---
description: Bot Commands
---

# Commands

### General Commands

| Command                                              | Description                                  | Example     |
| ---------------------------------------------------- | -------------------------------------------- | ----------- |
| <p><strong>/karuta</strong><br><strong></strong></p> | To see what's the bot support karuta feature | /karuta     |
| **/version**                                         | To see a version of the bot                  | /version    |
| **/support**                                         | the way to contact support                   | /support    |
| **/ping**                                            | Show bot's latency                           | /ping       |
| **/help**                                            | Show Bot Help                                | /help       |
| **/serverinfo**                                      | Show your server's configuration info        | /serverinfo |

### Karuta Commands

| Command   | Description                                                                                                                     | Example                               |
| --------- | ------------------------------------------------------------------------------------------------------------------------------- | ------------------------------------- |
| **/role** | <p>Add a role by yourself</p><p>Available for (<strong>wish watch</strong>, <strong>server drop watch, event drop</strong>)</p> | /role server-drop-watch active:True   |
| **estar** | add drop message to starboard manually                                                                                          | reply drop message and type **estar** |

### Admin Commands

| Command                          | Description                                                                                     | Example                                                       |
| -------------------------------- | ----------------------------------------------------------------------------------------------- | ------------------------------------------------------------- |
| **/remaining**                   | Check server premium plan remaining                                                             | /remaining                                                    |
| **/set starboard (Premium)**     | Set up starboard for premium                                                                    | /set starboard channel:#🌟│starboard active:True wishlist:200 |
| **/set starboard (Non-Premium)** | <p>Set up starboard, Can set channel only</p><p>Use <code>estar</code> for add to the board</p> | <p>/set starboard </p><p>channel:#🌟│starboard </p>           |
| **/starboard-status**            | Checking Starboard Server Config                                                                | /starboard-status                                             |
| **/set server-drop-watch**       | Enable or disable the **server drop** ping in your server.                                      | /set server-drop-watch active:True                            |
| /**set wishlist-drop-watch**     | Enable or disable the **wishlist drop** ping in your server.                                    | /set wishlist-drop-watch active:True                          |
| /**set event-drop-watch**        | Enable or disable the **event drop** ping in your server.                                       | /set event-drop-watch active:True                             |
| **/set pog-drop-ping**           | Enable or disable the **POG drop** ping role in your server.                                    | /set pog-drop-ping role:@Orange                               |

