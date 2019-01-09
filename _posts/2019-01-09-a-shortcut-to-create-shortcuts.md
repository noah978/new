---
title: "A Shortcut to Create Shortcuts"
layout: post
date: 2019-01-09 11:27
tag: 
- ios
- siri
- gba4ios
headerImage: false
description: "A Siri Shortcut that creates a home screen icon for a game in your GBA4iOS library."
category: blog
author: noah
---

Siri Shortcuts were introduced with iOS 12 and is considered one of the most impressive improvements to Siri ever. Apple realized that meeting every possible need or request in Siri was nearly impossible. But if they gave users the ability to create any set of chained commands to fulfill their request, they could *vastly* improve Siri’s capabilities.

Given the capabilities of the Siri Shortcuts app, I created a shortcut to help with my favorite emulator: GBA4iOS.

### Introducing,

# GBA4iOS Home Screen Shortcut Creator

Using this shortcut, you can create a Home Screen Icon using any image you want, that when clicked will directly open into any game in your GBA4iOS library. All you need to do is have an image and the exact name of your game as it appears in your library.

## How Does This Work?

Back when GBA4iOS was being developed, the developer Riley Testut implemented a feature that allowed a URL scheme to open games in GBA4iOS. A URL scheme looks like the following: ```gba4ios://Pokemon%20Emerald```

When you input the name of your game, the home screen shortcut creator then runs another separate shortcut which will convert regular text into a URL compatible text. So anytime you use the shortcut it's actually the same as typing the URL scheme into safari!

## How To Use

To use the shortcut you will need to add both of the following shortcuts to your Siri Shortcut library. This can be done by simply clicking the links on your device.

[GBA4iOS Shortcuts](https://www.icloud.com/shortcuts/7bfa1214a1b44f608e549475af67a6cc)

[Convert Text to URL](https://www.icloud.com/shortcuts/26dc3ef24a6c47f1ac8598365c84b352)

Just click the “GBA4iOS Shortcuts” (which is now in your siri shortcuts library) and it will guide you along the process. I would recommend copying and pasting the name of your game to ensure that it is exact.