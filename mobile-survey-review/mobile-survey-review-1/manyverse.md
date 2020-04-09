# ManyVerse

![](../../.gitbook/assets/manyverse-icon-small.png)

{% embed url="https://www.manyver.se/" caption="" %}

> Manyverse is a social network app using the SSB protocol \(Secure Scuttlebutt\) where you can write posts and share with friends nearby or over the internet. It's different from mainstream social networks because your data is yours, it lives on your phone, not in the cloud. So there is no login, no company holding your data, no ads, no tracking of your activity, it's just you and your friends! The app is free and open source software, and it will always remain free. \(iOS App Store\)

## Onboarding

![](../../.gitbook/assets/manyverse-onboard.png)

The ManyVerse onboarding flow is thorough and explanatory, albeit a lot of reading for a new user.

![](../../.gitbook/assets/manyverse-screen-7.PNG)

When setting up the app for the first time the user encounters a normal pattern of setting up an account or restoring one.

When a new account is setup however, there is no indication or notification that the account has been setup, nor of the profile that has been setup for them.

![](../../.gitbook/assets/manyverse-screen-9.PNG)

If the user would like to restore an account they need to enter in a not terribly friendly 48 word recovery phrase. While this is no doubt highly secure, and despite essentially functioning like a password for the user, there could be other recovery options available.

![](../../.gitbook/assets/manyverse-screen-11.PNG)

Once a profile is created or recovered, the user then is presented with their profile screen which is a list of messages \(in this case blank as it's a new user\).

### Profile and settings

![](https://github.com/ipfs/mobile-design-guidelines/tree/c30d2d6a1b009d38d16b7babc146d1c1f8604f13/.gitbook/assets/manyverse-screen-11%20%281%29.PNG)

The default UI screen is the Messages screen where the user would compose and read messages they would receive once connected and synced via Scuttlebutt.

![](../../.gitbook/assets/manyverse-screen-10.PNG)

App navigation is handled by the navigation \(“hamburger”\) menu as is customary with the Google Material UI which ManyVerse uses.

![](https://github.com/ipfs/mobile-design-guidelines/tree/c30d2d6a1b009d38d16b7babc146d1c1f8604f13/.gitbook/assets/manyverse-screen-15%20%281%29.PNG)

From the main side secondary navigation the user can see the database. There are no controls for what is in that database, as nothing in ManyVerse can be deleted. The database entries can be tapped and then the source code for each entry can be viewed.

![](https://github.com/ipfs/mobile-design-guidelines/tree/c30d2d6a1b009d38d16b7babc146d1c1f8604f13/.gitbook/assets/manyverse-screen-12%20%281%29.PNG)

The profile screen doesn't provide any options outside of Name and Bio text fields as well as a profile photo.

![](../../.gitbook/assets/manyverse-connections.png)

The Connections screen, despite having a multitude of options to connect to other ManyVerse or Scuttlebutt users, for instance via the Wifi network the user is currently on, via P2P or via a P2P pub server, it is only possible to get onto any of these from the start it seems by getting an invite to a pub server or having another person on the same network as you. This makes discovery extremely difficult for the user.

## Messaging

![](../../.gitbook/assets/manyverse-screen-14.PNG)

Messaging seems rather straight forward in ManyVerse, with a threaded view and Like and Comment buttons as well a colour scheme just like Facebook.

![](../../.gitbook/assets/manyverse-screen-22.PNG)

Upon clicking around the UI, I was somehow able to as a user to connect to myself on the Wifi network. At this point I was also able to follow myself which was unclear how this happened as well as what led me to this. There is a chance that while looking for pub servers on the Mac desktop Patchwork client that it somehow enabled this over the network, but for a novice absolutely nothing was clear. Also there is an obvious usability problem in being able to connect to yourself, or having multiple identities potentially running on the same app at the same time with no audit trail for the connections.

![](../../.gitbook/assets/manyverse-screen-23.PNG)

Viewing a user's profile and messages is rather straightforward, as is the ability to follow that user and view their bio.

## Summary

* Available on both iOS and Android
* At first glance simple to use, however once the user gets into it navigation and the logic of the app can become very confusing
* Account handling is unclear and there is little in-app instruction as to how user profiles are stored
* Appears to be able to do as it says which is online-offline syncing of messages and content and media in images which can be useful
* Connecting to other users is difficult and unclear

