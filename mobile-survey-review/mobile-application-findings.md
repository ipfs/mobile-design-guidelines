# Mobile Application Findings

The applications were investigated to learn what features and interface components and patterns work and what may not work for users in designing future IPFS applications for mobile.

## ManyVerse

| Finding | Recommendation |
| :--- | :--- |
| Connection status is not shown when the user logs in, they need to go to Connections screen | Provide quick and temporary alert telling the user their connection status |
| Identity and accounts not handled with a typical login and password | Show the user how other types of identity and holding of accounts work with an additional informational screen |
| Syncing status of content is not made apparent to the user  | If there is a syncing ability in the app, the user should be notified of its status and allow them to cancel if they want |
| There is no logout option unless the user closes the app | If the user needs to sign in, they should have the ability to sign out |
| Users can be connected to and sent images without confirmation | If chat allows for files like images to be sent, require confirmation to send for the user |
| When a new account is setup, there is no indication to the user that the account has been setup successfully | Show confirmation that profiles and other settings are done and okay |

## Sharedrop

* When making the user aware of privacy and connection implications with sharing, the information needs to be provided in a succint way with links to further information
* If there are multiple avatars or identities present, the user needs to be identified, for instance showing the users profile amongst others as "You"
* Always show the user where they are at in the sharing process
* If a confirmation code or link needs to be sent to another user, provide a method of doing that in the UI directly

## Status

* > Solid and user friendly blockchain app which enables relatively inexperienced users to get started with blockchain dApps
* While the sign-on process is typical and smooth for a blockchain app, it might be confusing to those who just wish to use P2P without public and private keys and maintaining them
* Onboarding processes intros should always have an option to login directly
* Make the user aware if necessary that they will need to manage public and private encryption keys
* Discoverability in finding other users and being made known to them should be done in app whenever possible
* Chat functionality should meet user expectations in features, such as attaching images and files
* Fetching and syncing of files should be automatic and not require addtional interaction
* Posting messages to community chats or boards should happen from its own interface, and not from a contextual menu in a user to user chat screen
* Interactions around difficult to understand themes such as blockchain are helped with imagery

## FrostWire

* Any UI personlisation should happen in hidden options, not during onboarding
* Separate different types of file transfers visually but present together, for instance downloading and seeding
* Useful for mobile downloads of music and video, but probably not for teams use and collaboration

## uTorrent Mobile

* If giving the user the option to search and discover, use the native app and not an external web site
* Don't provide any additional functionality that isn't related to the core functionality of the app
* Global app navigation should be for functionality and not second-order functionality like filtering
* Only show granular details of details if helps the user

## Haven

> Haven is a well designed and user-friendly app that does away with a lot of the upfront key and profile management often present in apps involving P2P purchases and cryptocurrency wallets.

* Tell the user as quickly as possible what the application does and what it means for them
* Don't provide to the user multiple, unrelated places where they can do the same actions
* Initiating chats without invites or acceptances which could be a privacy concern for many users
* Don't use design patterns from other operating systems, it might confuse users not familiar with them

## Fairdrop

* If the user needs to have an account, they need to be told why and what benefit it has
* Keep interaction as simple as possible
* If a link needs to be sent, allow the user to send via OS level features

