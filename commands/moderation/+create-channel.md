---
description: Creates a new channel
---

# +create-channel

## Usage

```
+create-channel <name> {type (text/voice/category/stage/forum)}
```

## Arguments

| Name                                    | Description              | Type   | Required |
| --------------------------------------- | ------------------------ | ------ | -------- |
| name                                    | The name of the channel. | String | Yes      |
| <mark style="color:purple;">type</mark> | The type of the channel. | Enum   | No       |

### Possibilities for <mark style="color:purple;">`type`</mark>

* **`text`**
* **`voice`**
* **`category`**
* **`stage`**
* **`forum`**

{% hint style="info" %}
If no type is specified, a text channel will be created.
{% endhint %}

## Examples

![](https://user-images.githubusercontent.com/111157596/236548363-aa2e6ba4-131b-483a-adfe-0f66f59cfb05.png)
![](https://user-images.githubusercontent.com/111157596/236548430-452d2097-bc2e-45e0-8c52-4e85a4167ede.png)
