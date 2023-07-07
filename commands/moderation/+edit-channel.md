---
description: Edits the specified channel's property
---

# +edit-channel

## Usage

```
+edit-channel <channel> <property (name/topic/position/category/nsfw)> <new name/topic/position/categoryID/nsfw (yes/no)>
```

## Arguments

<table><thead><tr><th width="155">Name</th><th width="289">Description</th><th width="122">Type</th><th>Required</th></tr></thead><tbody><tr><td>channel</td><td>The channel to edit.</td><td>Channel</td><td>Yes</td></tr><tr><td><mark style="color:purple;">property</mark></td><td>The property of the channel to edit.</td><td>Enum</td><td>Yes</td></tr><tr><td>new name<br>new topic<br>new position<br>new categoryID<br>new nsfw</td><td>The new channel name.<br>The new channel topic.<br>The new channel position.<br>The new channel category.<br>The new channel NSFW setting.</td><td>String<br>String<br>Number<br>Category<br>Boolean</td><td>Yes</td></tr></tbody></table>

### Possibilities for <mark style="color:purple;">`property`</mark>

* `name` - To edit the channel's name.
* `topic` - To edit the channel's topic.
* `position` - To edit the channel's position.
* `category` - To edit the channel's category.
* `nsfw` - To edit the channel's NSFW setting.

## Examples

![](https://user-images.githubusercontent.com/111157596/251847194-82e3ef3d-36f0-44d4-b6e9-86c33c31e8a3.png)
![](https://user-images.githubusercontent.com/111157596/251847272-efe28e3b-5492-4343-ba87-b7987f7e93f8.png)
![](https://user-images.githubusercontent.com/111157596/251847311-fa1e5734-fc19-4fb9-a2cd-8938acd0b3fd.png)
![](https://user-images.githubusercontent.com/111157596/251847366-b42deb30-6b8d-452c-a00b-21536773b9da.png)
![](https://user-images.githubusercontent.com/111157596/251847473-b1a016bc-f61c-495e-b9ec-c3589c0a6ade.png)
