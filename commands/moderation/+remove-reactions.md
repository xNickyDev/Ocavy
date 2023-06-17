---
description: Removes reactions from a message
---

# +remove-reactions

## Usage
```
+remove-reactions <channel> <messageID> {all/emoji...}
```

## Arguments
Name | Description | Type | Required
:-- | :-- | :-- | :--
channel | The channel of the message. | Channel | Yes
messageID | The ID of the message. | Message | Yes
all<br>emoji... | Removes all emojis from the message.<br>Removes the provided emojis from the message. | Enum<br>Emoji | No

{% hint style="info" %} If no value or "all" is specified for the last argument, all emojis of the message are removed. If you specify emojis to remove, only those emojis will be removed. You can specify up to **5** emojis. {% endhint %}

## Examples
![](https://user-images.githubusercontent.com/111157596/246607910-55e58cd4-8916-4fad-ae1c-cb690e182683.png)
![](https://user-images.githubusercontent.com/111157596/246607916-2083ef4b-ccf8-4600-920c-14b053710c85.png)
![](https://user-images.githubusercontent.com/111157596/246607927-6cf701c9-6d80-4fcd-9368-f3ff36661e0a.png)
