# +slowmode
Enables/Disables slowmode in a channel

## Usage
```
+slowmode {#channel} <duration>
```

## Arguments
Name | Description | Type | Required
:-- | :-- | :-- | :--
#channel | The channel for the slowmode. | Channel | No
duration | The duration of the slowmode cooldown. | Alphanumeric | Yes

### Duration types
- **`s`** - seconds
- **`m`** - minutes
- **`h`** - hours

Examples: `4s`, `4m`, `4h`

## Disable slowmode
To disable the slowmode simply use `0` or `off` as duration.

> **Note** : If no channel is mentioned the slowmode will be enabled/disabled in the current channel.

## Examples
![](https://tawk.link/60e18ecd649e0a0a5cca7167/kb/attachments/g7PLxHOA-k.jpg)
![](https://tawk.link/60e18ecd649e0a0a5cca7167/kb/attachments/CkKgdrZA1a.jpg)
![](https://tawk.link/60e18ecd649e0a0a5cca7167/kb/attachments/hf6DDBnNLY.jpg)
