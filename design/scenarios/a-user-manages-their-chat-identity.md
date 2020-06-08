# A user manages their chat identity

Messaging requires a network of users. Getting started messaging with other people requires knowing people connected to one another. Second to this is discovering and safely connecting to them.

## What we found out in research

* Discoverability of other chat users is sometimes overlooked to [provide more security](application-survey/application-survey/manyverse)
* Users need to start chatting to other users as [quickly and painlessly](application-survey/application-survey/haven) as possible to be engaged with your app

## Design considerations

* Since IPFS can work without a connection to the Internet, there should be an easy way for the user to send a link to connect offline
* Allow the user to set if they are discoverable to other users
* Allow the user to control confirmations of new contacts and chats
* Give the user easier to recover profile key recovery options

### Who is the user and what are their needs

Messaging app user interested in using P2P chat because its more secure and can work without Internet access. There is also concern apps like this will be hard to use.

## Putting it into practice

### Getting started to chat on App Y

The user has downloaded, installed and setup their profile on App Y. They do not have any contacts yet.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ManagingIdentity-1.png)

### The user views profile

The user views their profile to make sure they are discoverable to colleagues. They also see options for their profile as well as other means how to invite other App Y users to chat. They can invite other users by sending their profile link. They can show the QR code or send the link through Bluetooth, Messaging app or Email.

The user looks at their profile recovery to feel safe about their profile. During onboarding they needed to generate a key. They were then told that they would be able to save a phrase to make new keys if they logged out or lost their phone.

They make sure to uncheck `Require new contact confirmation` so if anyone finds them they don't have to confirm them starting a chat.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ManagingIdentity-2.png)

> **Design considerations**
>
> Allow the user to set if they are discoverable to other users
>
> Allow the user to control confirmations of new contacts and chats

### The user searches for someone to add as a contact

Their colleague told them to search for their user name \("Bobby124"\) to add them as a contact. The other user made their profile discoverable so it appears in the search result. The user can then send them a message which will appear in the `Chat` screen.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ManagingIdentity-3.png)

### A chat is started with the contact

After the user found their colleague, they were able to start a chat with them. This is because their colleague didn't need confirmation to start a chat with them.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ManagingIdentity-4.png)

