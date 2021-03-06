---
title: "A Shortcut to Create Shortcuts"
layout: post
date: 2019-01-09 11:27
tag:
- ios
- siri
- gba4ios
- delta
headerImage: false
description: "A Siri Shortcut that creates a home screen icon for a game in your GBA4iOS (or Delta!) library."
category: blog
author: noah
---

Siri Shortcuts were introduced with iOS 12 and is considered one of the most impressive improvements to Siri ever. Apple realized that meeting every possible need or request in Siri was nearly impossible. But if they gave users the ability to create any set of chained commands to fulfill their request, they could *vastly* improve Siri’s capabilities.

Given the capabilities of the Siri Shortcuts app, I created a shortcut to help with my favorite emulators: [GBA4iOS](https://gba4iosapp.com) and the more recent and capable [Delta.](https://deltaemulator.com)

### Introducing,

# My iOS Emulator Home Screen Shortcut Creator

Using this shortcut, you can create a Home Screen Icon using any image you want, that when clicked will directly open into any game in your rom library. All you need to do is have an image and the exact name of your game (or in Delta's case, the deep link) as it appears in your library.

## How Does This Work?

Back when GBA4iOS was being developed, the developer Riley Testut implemented a feature that allowed a URL scheme to open games in GBA4iOS. This same feature is also present in Delta. A URL scheme looks like the following:

``gba4ios://Pokemon%20Emerald``

~ or ~

``delta://game/989bcb79c779cv97``

In the case of GBA4iOS, when you input the name of your game, the home screen shortcut creator then runs another separate shortcut which will convert regular text into a URL compatible text. So anytime you use the shortcut it's actually the same as typing the URL scheme into safari!

Delta's shortcut is even simpler since the deep link doesn't have any characters that need to be converted to URL compatible text.

## How To Use

To use the GBA4iOS shortcut you will need to add both of the following shortcuts to your Siri Shortcut library. This can be done by simply clicking the links on your device.

[GBA4iOS Shortcuts](https://www.icloud.com/shortcuts/eab5089ca3fd4faaa910b79eed6735f3)

[Convert Text to URL](https://www.icloud.com/shortcuts/63d051ede25c4d63b3dd31f9f4422039)

Just click the “GBA4iOS Shortcuts” (which is now in your siri shortcuts library) and it will guide you along the process. I would recommend copying and pasting the name of your game to ensure that it is exact.

For Delta, you only need to add the following shortcut to your siri shortcut library:

[Delta Shortcuts](https://www.icloud.com/shortcuts/b5207b88f7464381aa4d487878496259)

## Credits

Thank you to Riley Testut for creating GBA4iOS and Delta! And for including URL Scheme support in both!

Thank you to Federico Viticci for creating the [Home Screen Icon Creator](https://www.macstories.net/ios/home-screen-icon-creator-a-shortcut-to-create-custom-icons-for-apps-contacts-solid-colors-and-more/) shortcut, which I modified to create the GBA4iOS Shortcut creator.
