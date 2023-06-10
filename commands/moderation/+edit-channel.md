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

<figure><img src="../../.gitbook/assets/Bildschirmfoto 2023-06-10 um 15.01.56.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Bildschirmfoto 2023-06-10 um 15.02.22.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Bildschirmfoto 2023-06-10 um 15.03.01.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Bildschirmfoto 2023-06-10 um 15.03.24.png" alt=""><figcaption></figcaption></figure>

<figure><img src="../../.gitbook/assets/Bildschirmfoto 2023-06-10 um 15.03.43.png" alt=""><figcaption></figcaption></figure>
