# Changelog

## 2023

### Changelog

* Added system "Logging" to `/toggle`
* Removed `+enable-logs` (Deprecated)
* Removed `+disable-logs` (Deprecated)
* Added `/config-logging`
* Made it possible to calculate with decimals at `+calculate`
* Made it possible to use multiple `0` in a number at `+calculate`
* Added `+hangman`
* Added **Reason** field to logging action "User Banned (Auto)"
* Added `+kill`
* Made it possible for `+quote` to quote messages by replying to them
* Updated `+dog`
* Fixed `Command Info` commands returned messy/incorrect information
* Officially added `+changelog`
* Partly fixed `+timezones`, `+timezone-info` and `+change-timezone` not working properly. If you encounter any issue with these commands, keep executing the command/action
* Fixed incorrect count number in the **Reactions** field of `+reaction-info`
* Fixed `+neko` requiring arguments when executing
* Fixed `+cat`
* Officially added `+kill`
* Removed the image link from the emoji at `+emoji-info`
* Added `+id-info`
* Made it possible for `+get-id` to get the message ID of a message by relying to it

## 2022

### Changelog 11/23/2022

* Fixed `+close` is returning wrong error message when using the command in an already closed ticket
* Added channel types `stage` and `forum` to `+create-channel`
* Added alias `search` to `+google`
* Updated & Optimized `+google`
* Added Ocavy's GitBook documentation link to `+invite`
* Added `/create-channel`
* Updated `+weather`
* Fixed `+screenshot` is converting the specified link into all lowercase
* Fixed `+invite-info`
* Replaced +give-role and +take-role with `+role` & added new option `removeall`
* Added `/role`
* Added `+anime`
* Fixed Command Info commands weren't working
* Made `+calculator` author-only
* Updated & Optimized `+user-info`
* Fixed `/user-info` not working in DMs
* Added `+auto-role`
* Added `/auto-role`
* Added `/toggle`
* Added **Boost Count** field to `+server-info`
* Added buttons to the ticket message when creating tickets via panel
* Fixed the modal of `+panel` is displaying an error after creating a new ticket
* Fixed sometimes no ephemeral message is sent after ticket creation with `+panel`
* Added **Category** field to `+channel-info`
* Added **Position** field to `+channel-info`

### Changelog 10/09/2022

* Fixed some APIs wasn't working
* Added `+command-info` (Aliases: `+help`, `+command`)
* Added optional `command` argument to `+help` and `/help`
* Made it possible to receive **limited** emoji information by specifying just the ID at `+emoji-info`
* Fixed that sometimes an error message pops up although the selected emoji is valid at `+emoji-info`
* Improved the interaction loading cooldown at `+akinator`. It should be a little bit more stable now
* Added `+steal-emoji` (Alias: `+steal`)
* Changed the default image size to **2048** at `+avatar`
* Added buttons "Normal Avatar" and "Server Avatar" to `+avatar` (they only show up when the specified user has a server avatar)
* (BETA) Modified `+create-role`. You can now create roles way easier and with more options in 3 steps
* Removed the "Roles" field at `+user-info` & instead added new **Highest Role** field
* Added **Badges** field to `+user-info` (currently only hypesquad badges are supported)
* Made it possible for `+invite-info` to receive guild invite data if the invite could not be detected and is from the current server
* Added `+twitter`
* Fixed & Reworked `+youtube`
* Added aliases `warns` and `warnings` to `+check-warns`
* Added `/review`
* Fixed `+user-info`
* Fixed `+instagram`
* Added **Ticket Category** field to `+ticket-info`

### Changelog 08/01/2022

* Added **Reactions** field to `+reaction-info`
* Fixed `+weather`
* Added modals for a ticket subject when creating tickets via panel
* Fixed that buttons stay after pressing in the ticket's close and delete messages
* Made it possible to specify a subject when creating tickets with `+ticket`
* Updated `+delete-role`
* Added `/delete-role`
* Added `+screenshot` (Alias: `+ss`)
* Added `+tictactoe` (Alias: `+ttt`)
* Made it possible for `+banner` to receive banners from users not on the current server
* Made `+banner` functional in DMs
* Updated `+reset-ticket-message`
* Updated `+change-mod-role`
* Made it possible for `+avatar` to receive avatars from users not on the current server
* Made `+avatar` functional in DMs
* Fixed, Updated and Optimized `+create-channel`
* Added `+server-banner`
* Added `+server-splash`
* Made `+chat` functional in DMs
* Made `+rps` functional in DMs
* Updated `+pin`
* Updated `+unpin`
* Updated `+reaction-info`
* Added timestamps to `+user-info`
* Added `+akinator` (Alias: `+aki`)
* Fixed `+banner`
* Fixed `+color-info` not working in DMs
* Fixed "roles could not be displayed" bug at `+user-info` and `+user-roles`
* Fixed and Added the role mentions at `+server-roles`
* Fixed `+screenshot`
* Fixed `+meme`

### Changelog 05/27/2022

* Updated `+color-info`
* Deleted `+panik`
* Updated `+clear`
* Updated `+channel-info`
* Made `channel` option optional at `/channel-info`
* Added `+bubbles`
* Updated `+user-perms`
* Made `user` option optional at `/user-perms`
* Fixed `+user-perms` is displaying permissions incorrectly
* Added all missing permissions to `+user-perms`
* Added `+remove-member`
* Updated `+add-member`
* Improved tickets
* Improved `+get-id`'s emoji argument
* Updated `+slowmode`
* Added `+neko`
* Added `+hug`
* Added `+kiss`
* Added `+cuddle`
* Added `+slap`
* Added `+cry`
* Added `+bite`
* Added `+feed`
* Added `+pat`
* Officially added `+placeholders`
* Updated `+user-info`
* Made it possible for `+user-info` to receive information about a user not on the current server
* Made `+user-info` functional in DMs
* Officially added `/create-thread`
* Moved `+set-ticket-message` to modals
* Added category choices to `/help`
* Fixed `+color-info`
* Updated `+ticket-info`
* Added logging for `+timeout`
* Added logging for `+untimeout`

### Changelog 04/20/2022

* Renamed the select menu option "Privacy Policy" to **Guidelines** in help command
* Added title URL to `+user-info` which immediately opens the Discord user profile when clicking it
* Fixed that a comma is displayed after the last username in the **Reacted Users** field at `+reaction-info`
* Updated `+set-muted-role`
* Updated `+change-nickname`
* Updated `+set-ticket-category`
* Added `+ping`
* Updated `+edit-channel`
* Added arguments `position`, `nsfw` and `category` to `+edit-channel`
* Added `+edit-role`
* Made it possible to ban users not on the current server by using userID
* Server count of Ocavy is now being updated on top.gg and discordbotlist.com
* Updated `+close`
* Added a confirmation message to `+close` instead of closing the ticket directly after executing the command
* Updated `+timezones`
* Added select menu and all available timezones to `+timezones`
* Updated `+change-timezone`
* Added `+timezone-info`
* Set the default timezone from Europe/Berlin to **Etc/UTC** (standard)
* Made it possible to quote embed messages with `+quote`
* Updated `+invite-info`
* Made it possible to receive invite information about invite links from other servers (not current server limited anymore)
* Added `/invite-info`

### Changelog 03/05/2022

* Fixed at `+user-roles` and `+user-info` that mentioning a role is causing to display the role x times
* Deleted `+trash`
* Updated `+create-role`
* Updated `+get-id`
* Added slash command `/create-role`
* Added back `+translate`
* Fixed FINALLY many bugs regarding tickets
* Optimized some button response styles of tickets
* Finally fixed longest bug that existed! Fixed that bot isn't adding warnings after the first warning
* Fixed that reasons count number in **Reasons** stopped continue counting after second warning and just counted like 1, 2, 2, 2,... at `+check-warns`
* Updated `+mute`
* Updated `+unmute`
* Fixed (hopefully) `+invite-info`
* Added `+remove-warns`
* Fixed/Updated `+server-roles`
* Fixed/Updated field **Roles** in `+user-info`
* Ticket message is now being pinned in tickets to find them easier
* Added slash command `/delete-channel`
* Added argument `emoji` to `+get-id`
* Updated Ocavy's bot page descriptions at Top.gg and discordbotlist.com
* Made it possible to get emoji information with provided emoji name at `+emoji-info`

### Changelog 02/16/2022

* Fixed `+banner`
* Added field **Animated** to `+emoji-info`
* Added `on-Ban-Added` logging
* Added `on-Ban-Removed` logging ([https://media.discordapp.net/attachments/816767374610923601/942065891141627964/Screenshot\_20220125-234924\_Discord-Beta.jpg](https://media.discordapp.net/attachments/816767374610923601/942065891141627964/Screenshot\_20220125-234924\_Discord-Beta.jpg))
* Added `on-Message-Deleted` logging
* Added `+quote`
* Updated `+server-info`
* Fixed `+set-mod-role`
* Added ephemeral response to ticket panel ([https://media.discordapp.net/attachments/816767374610923601/939506931469533234/Screenshot\_20220205-140227\_Discord.jpg](https://media.discordapp.net/attachments/816767374610923601/939506931469533234/Screenshot\_20220205-140227\_Discord.jpg))
* Fixed that time in ticket message is displayed incorrectly by creating tickets with ticket panel
* Updated `+give-role`
* Updated `+take-role`
* Renamed `+delete-reactions` to `+remove-reactions`
* Updated `+remove-reactions`
* Added optional argument `{emoji}` to `+remove-reactions` (at least 5 emojis can be selected)
* Updated `+user-info`
* Fixed that `+user-roles` don't respond when provided user has no roles

### Changelog 01/17/2022

* Removed `+playstore` due permanently broken api
* Disabled `+translate` due api errors
* Disabled `+youtube` temporarily
* Fixed `+user-banner` (changed api due host errors)
* Added select menu to `+server-icon` (customize image format and size)
* Added select menu to `+avatar` (customize image format and size)
* Made minor changes to `+timeout`
* Made minor changes to `+untimeout`
* Roles in `+user-roles` are sorted from highest role now
* Added user roles count to `+user-roles`
* Updated `+delete-channel`
* Updated `+delete-role`
* Updated `+change-nickname`
* Updated `+kick`
* Updated `+ban`
* Updated `+warn`
* Updated `+unban`
* Fixed `+ban` is being triggered by executing `+banner`
* Renamed `+user-banner` to `+banner` and added `user-banner` as alias instead
* Added alias `user-avatar` and `av` to `+avatar`
* Updated `+enable-logs`
* Updated `+disable-logs`
* Updated kick, ban, unban and warn logs
* Fixed `+calculator`
* Fixed `+avatar` is being triggered by executing +leave

### Changelog 01/02/2022

* Added slash as category to commands help
* Added slash command `/channel-info`
* Added slash command `/color-info`
* Added slash command `/role-info`
* Added slash command `/user-perms`
* Added slash command `/user-info`
* Added slash command `/emoji-info`
* Added slash command `/invite`
* Added slash command `/create-emoji`
* Made it possible to receive commands help by pinging Ocavy
* Updated `+set-mod-role` (added role id and name arguments, minor changes)
* Updated `+change-mod-role` (added role id and name arguments, minor changes)
* Updated `+give-role` (fixed weird errors, minor changes)
* Added `+pin`
* Added `+unpin`
* Added `+timeout`
* Added `+untimeout`
* Fixed bug that emoji is not displaying in embed after creation at `+create-emoji`
* Fixed/Added at `+lyrics` special character escaping
* Fixed getting invites at `+invite-info`

## 2021

### Changelog 11/28/2021

* Got the Select Menu of `+help` finally working again
* Added Select Menu-Option "Privacy Policy"
* Added string "image" to slash command `/embed` (Value: URL needed)
* Added boolean "timestamp" to slash command `/embed` (Value: true or false)
* Made `+help` and `/help` category/message not case sensitive
* Made minor changes
* Added "Add to Server" button to Ocavy (PC supported only for now) https://cdn.discordapp.com/attachments/893231315581800459/914545611989217300/Bildschirmfoto\_2021-11-28\_um\_16.56.37.png
* Added `+invite`
* Added `+user-roles` as Beta Version (will be optimized soon)
* Added **Ocavy Privacy Policy** (https://discord.com/channels/790676954247725106/791812035720904714/911697037110673448)
* Changed some embeds color hex from #7289DA to #5865F2

### Changelog 11/13/2021

* Added slash command `/embed` (reaction bugged)
* Added article **Slash Embed Guide** to our Help Center ([https://ocavy-support.tawk.help/article/slash-embed-guide](https://ocavy-support.tawk.help/article/slash-embed-guide))
* Added an article/section for **Advanced Commands Help** at our Help Center
* Updated section/category **Bugs** at our Help Center
* Added `+panel`
* Added string "category" to slash command `/help`
* Redesign of all Help Commands
* Added author link to Help Commands (leads to Advanced Commands Help article)
* Disabled `+playstore` due errors
* Fixed 2 errors at `+lyrics`

1. Escaped empty fields displaying when song not found (https://media.discordapp.net/attachments/816767374610923601/909160031591727104/Screenshot\_20211113-201551\_Discord-Beta.jpg)
2. Escaped brackets in songs breaking the whole code
