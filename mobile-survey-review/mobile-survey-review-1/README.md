# Mobile Application Survey

We have chosen and tested a variety of available, meaning publicly released software available on app stores or through mobile web, apps to understand previous approaches to designing and developing mobile P2P applications. We have not found that many stable and publicly released mobile applications in the P2P space as most development has concentrated on the desktop. The apps we found were from iOS and Android app store searches as well as from referrals to various P2P platforms in development.

The applications in the Mobile Application Survey all share P2P as the transport layer but vary drastically in feature sets, allowing us to see a broad spectrum of current use cases. This will help us help others design better and more useful apps, choosing the right features, and how to implement them in an interface that works for users. What follows are summaries of how the apps work for users to be used in comparing feature sets and for findings to inform further design.

> The purpose is to identify what p2p  
> was used for in each app, and where it surfaced in the user  
> experience. Should remove the editorial critique of good/bad and stick  
> to observational findings.

## [ManyVerse](manyverse.md)

* Available on both iOS and Android
* Uses SSB \([Scuttlebutt](https://www.scuttlebutt.nz)\) communications and syncs via Bluetooth, LAN, or internets
* When a new account is setup there is no indication or notification to the user that the account has been setup successfully, nor of the profile that has been setup for them
* Appears to be able to do as it says which is online-offline syncing of messages and content and media
* Connecting to other users requires explicit invites to or invites to "pubs" chat rooms

## [Sharedrop](sharedrop.io.md)

* Web app only \(tested on iOS Firefox, iOS Safari and Android Chrome\)
* HTML5 clone of Apple AirDrop service using WebRTC for secure P2P file transfer
* Does not require accounts or installation
* Avatars and anonymous profile names are used to identify users. Every time the browser window refreshes, they change
* The user is made aware they are sharing directly with another user
* A file transfer of a 2MB photo was instantaneous

## [Status](status.md)

* Available on both iOS and Android
* Messaging uses P2P Whisper protocol and end-to-end encryption
* Chat discoverability allows for finding of other users
* Does not have file transfer functionality built-in and any file transfer can only happen through a loaded dApp in the Browser 
* No ability to share files directly through through Chat.

## [FrostWire](frostwire.md)

* Torrent application available for mobile on Android only
* Freemium model with the app ad-supported unless upgraded to a month by month, 6 month or yearly terms. Also has a 30 minutes free with 1 video ad play
* Can download and seed torrents from the mobile client
* In-app torrent search
* User able to select which files in torrent they would like to download
* Has an integrated media library which also allows you to preview video and audio while downloading

## [uTorrent Mobile](utorrent-mobile.md)

* Torrent application available for mobile on Android only
* Torrent search is not integrated into the app and instead uses Google search web page
* Downloading sometimes requires the user to copy and paste the torrent link from a search results page and then add through the app manually
* Navigation Video and Music links do not search for or list Video and Music, but are filters for local files
* Features DLive, a live video stream site which features no torrent downloading or sharing
* Integrated media player

## [Haven](haven.md)

* Available on both iOS and Android
* Haven uses IPFS to run the OpenBazaar P2P network
* Users can sell and chat about items for sale, create post and make payments with cryptocurrency multiwallet
* Other users can be followed and messaged without invites or acceptances
* User does not need to create an account and can remain anonymous if they choose

## [Fairdrop](fairdrop.md)

* Web app only \(tested on iOS Firefox, iOS Safari and Android Chrome\)
* Runs on the Ethereum network and uses Swarm’s decentralised storage system for file storing and sending
* Ability to send files of up to 100 MB
* File transfer can be done anonymously
* Features accounts which allow the user to have a history of downloads and transfers

