---
description: >-
  This section will explain the various bracket and argument types used for
  command arguments. Command arguments are anything that goes in the brackets <>
  and {} of a command.
---

# Arguments

## Bracket Types

The bracket around an argument indicates whether the argument is required (must be included) or optional (can be included, but not required). There are three types of brackets that we use for Ocavy:

* `<>` - This argument is required, it **must** be included.
* `{}` - This argument is optional, it **can** be included but not required.
* `()` - This holds enum values for the argument, **one** option must be picked and specified.

{% hint style="warning" %}
**Do not include** the brackets (`<>`, `{}` and `()`) when using a command.
{% endhint %}

## Argument Types

<table data-full-width="true"><thead><tr><th width="139">Type</th><th>Description</th></tr></thead><tbody><tr><td>String</td><td>Used in most cases. A string can be any character or text.</td></tr><tr><td>Number</td><td>Any number without decimal.</td></tr><tr><td>URL</td><td>A valid domain link, must be prefixed by <code>http://</code> or <code>https://</code> and have a valid domain name.</td></tr><tr><td>Enum</td><td>Strings that match a certain key value provided in the <code>()</code> bracket right next to the argument name.</td></tr><tr><td>Emoji</td><td>Emoji as unicode (😄) or the Discord custom emojis (<code>&#x3C;a:emoji_name:emoji-id></code> for animated and <code>&#x3C;:emoji_name:emoji-id></code> for normal emojis) format.</td></tr><tr><td>Hex</td><td>A Color Hex code, e.g. <code>#ffffff</code> or <code>ffffff</code> (the <code>#</code> can be included).</td></tr><tr><td>Duration</td><td>A time based duration, an integer suffixed with a valid time format (<code>s</code>, <code>m</code>, <code>h</code>, <code>d</code>, <code>w</code>), e.g. <code>12m</code> or <code>3d</code>.</td></tr><tr><td>Timezone</td><td>A valid timezone, e.g. <code>America/New_York</code>. Find timezones using the <a href="commands/utility/+timezones.md"><code>+timezones</code></a> command.</td></tr><tr><td>Invite</td><td>A valid Discord server invite link or code, e.g. <code>https://discord.gg/DEEZY5cwpy</code>, <code>discord.gg/DEEZY5cwpy</code> or <code>DEEZY5cwpy</code>.</td></tr><tr><td>Boolean</td><td>One of: <code>yes</code>/<code>no</code> or <code>true</code>/<code>false</code>.</td></tr><tr><td>User</td><td>A valid Discord user ID, mention or name.</td></tr><tr><td>Role</td><td>A valid Discord role ID, mention or name.</td></tr><tr><td>Channel</td><td>A valid Discord channel ID, mention or name.</td></tr><tr><td>Category</td><td>A valid Discord category ID, mention or name.</td></tr><tr><td>Server</td><td>A valid Discord server ID or name.</td></tr><tr><td>Message</td><td>A valid Discord message ID.</td></tr></tbody></table>

## Pairs

<table><thead><tr><th width="123.22653721682846">Type</th><th>Description</th></tr></thead><tbody><tr><td>Ellipsis</td><td>Ellipsis notations (<code>...</code>) symbolize an argument that can be repeated multiple times. Ellipsis is denoted with <code>...</code> as the argument after the argument which can be repeated. Currently only used with <a href="commands/moderation/+remove-reactions.md"><code>+remove-reactions</code></a>.</td></tr></tbody></table>
