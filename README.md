# BetterDiscord-Embeds

A plugin for Better Discord that allows you to send fancy embed messages like this:

![Embed Example](https://raw.githubusercontent.com/Fraserbc/BetterDiscord-Embeds/master/images/embed_example1.PNG)

# Disclaimer!
## It is possible that Discord will ban and delete your account for using this plugin
I can not be held responsible if this happens. Using custom clients and plugins is a breach of Discord's Terms of Service.

# Installation
* Clone this repository
* Copy SendEmbeds.plugin.js to your plugins folder, you can access this by going into your user settings, plugins and clicking "Open Plugin Folder"

# Usage
```
    /e title:           Your title
    description:        Your description
    url:                The url your title sends you to when you click it
    color:              The hex color code of the embed
    timestamp:          True or False - If you want a timestamp at the bottom of your embed or not
    footer_image:       The url of the image in the footer
    footer:             The footer text
    thumbnail:          The url of the thubmnail image
    image:              The url of the main image
    author:             The name of the author
    author_url:         The url clicking the authors name send you to
    author_icon:        The url of the author's icon
```

The title should be enclosed in double quotes and there needs to be a `#` infront of the color code

Here's an example:

```
/e title: Command Army
description: Cool embeds
Wow! Multiline
url: https://discordapp.com
color: #1243ff
timestamp: true
footer_image: https://cdn.discordapp.com/embed/avatars/0.png
footer: WOW!
thumbnail: https://cdn.discordapp.com/embed/avatars/0.png
image: https://cdn.discordapp.com/embed/avatars/0.png
author: Commander 
author_url: https://discordapp.com
author_icon: https://cdn.discordapp.com/embed/avatars/0.png
```

## How do I do multiline embeds?

The same way you do it normally with `Shift + Enter`.
