---
description: Edits the specified channel's property.
---

# +edit-channel

## Usage
```
+edit-channel <channel> <property (name/topic/position/category/nsfw)> <new name/topic/position/categoryID/nsfw (yes/no)>
```

## Arguments
Name | Description | Type | Required
:-- | :-- | :-- | :--
channel | The channel to edit. | Channel | Yes
<mark style="color:purple;">property</mark> | The property of the channel to edit. | Enum | Yes
new name<br>new topic<br>new position<br>new categoryID<br>new nsfw | The new channel name.<br>The new channel topic.<br>The new channel position.<br>The new channel category.<br>The new channel NSFW setting. | String<br>String<br>Number<br>Category<br>Boolean | Yes

### Possibilities for <mark style="color:purple;">`property`</mark>
- `name` - To edit the channel's name.
- `topic` - To edit the channel's topic.
- `position` - To edit the channel's position.
- `category` - To edit the channel's category.
- `nsfw` - To edit the channel's NSFW setting.

## Examples
![](https://user-images.githubusercontent.com/111157596/244872278-d4e699a9-91bd-485a-b73a-7dc90c8aacd8.png)
![](https://user-images.githubusercontent.com/111157596/244872314-9955501a-9a56-47bf-8636-85f4d26544ea.png)
![](https://user-images.githubusercontent.com/111157596/244872322-a23cf544-d702-487f-b7e6-925c401b8b69.png)
![](https://user-images.githubusercontent.com/111157596/244872334-692cab15-fe74-4fa8-8d69-6cec80b7fc41.png)
![](https://user-images.githubusercontent.com/111157596/244872340-61a676a4-812b-425a-993e-beaa5f4f59b4.png)
