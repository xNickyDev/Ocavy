---
description: This section will explain the various bracket and argument types used for command arguments. Command arguments are anything that goes in the brackets `<>` and `{}` of a command.
---

# Arguments

## Bracket Types
The bracket around an argument tells you if the argument is required (must be included) or optional (can be included, but not required). There are three bracket types we use for Ocavy:
- `<>` - This argument is required, it **must** be included.
- `{}` - This argument is optional, it **can** be included but not required.
- `()` - This holds enum values for the argument, **one** option must be picked and specified.

{% hint style="warning" %} **Do not include** the brackets (`<>`, `{}` and `()`) when using a command. {% endhint %}

## Argument Types
Type | Description
:-- | :--
String | Used in most cases. A string can be any character or text.
Number | Any number without decimal.
URL | A valid domain link, must be prefixed by `http://` or `https://` and have a valid domain name.
Enum | Strings that match a certain key value provided in the `()` bracket right next to the argument name.
Emoji | Emoji as unicode (😄) or the Discord custom emojis (`<a:emoji_name:emoji-id>` for animated and `<:emoji_name:emoji-id>` for normal emojis) format.
Hex | A Color Hex code, e.g. `#ffffff` or `ffffff` (the `#` can be included).
Duration | A time based duration, an integer suffixed with a valid time format (`s`, `m`, `h`, `d`, `w`), e.g. `12m` or `3d`.
Timezone | A valid timezone, e.g. `America/New_York`. Find timezones using the [`+timezones`](./commands/utility/+timezones.md) command.
Invite | A valid Discord server invite link or code, e.g. `https://discord.gg/DEEZY5cwpy`, `discord.gg/DEEZY5cwpy` or `DEEZY5cwpy`.
Boolean | One of: `yes`/`no` or `true`/`false`.
User | A valid Discord user ID, mention or name.
Role | A valid Discord role ID, mention or name.
Channel | A valid Discord channel ID, mention or name.
Category | A valid Discord category ID, mention or name.
Server | A valid Discord server ID or name.
Message | A valid Discord message ID.

## Pairs
Type | Description
:-- | :--
Ellipsis | Ellipsis notations (`...`) symbolize an argument that can be repeated multiple times. Ellipsis is denoted with `...` as the argument after the argument which can be repeated. Currently only used with [`+remove-reactions`](./commands/moderation/+remove-reactions.md).
