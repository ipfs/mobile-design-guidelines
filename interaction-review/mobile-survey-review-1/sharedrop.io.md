# Sharedrop.io

{% embed url="https://sharedrop.io" caption="" %}

> **ShareDrop** is a peer-to-peer file sharing app powered by HTML5 WebRTC.

## Sharing

ShareDrop is a web application that also works on mobile. For testing purposes, it seemed to work in this case on Brave \(desktop/mobile\) and Safari \(mobile\). It had worked previously on Firefox \(desktop/mobile\) but that was not working for this particular testing.

![](https://github.com/ipfs/mobile-design-guidelines/tree/c30d2d6a1b009d38d16b7babc146d1c1f8604f13/.gitbook/assets/sharedrop-1%20%281%29.png)

The user is prompted with a modal showing how to use the app which they have to approve to continue.

![](../../.gitbook/assets/sharedrop-2.png)

On the sharing mobile \(in this case, desktop simulation in Brave\) any user with SharePoint open on the network shows as an animal avatar. In this case, showing the two test devices.

![](https://github.com/ipfs/mobile-design-guidelines/tree/c30d2d6a1b009d38d16b7babc146d1c1f8604f13/.gitbook/assets/sharedrop-3%20%281%29.png)

The connection verification between the two devices sharing is initiated by the device receiving the shared file by showing a QR code which the other device needs to read to verify. Alternately, the user can copy and send a code.

![](../../.gitbook/assets/sharedrop-4.png)

The connection is then verified. At that point the user clicks the avatar of the device they want to share with and then are given a system prompt \(in this case iOS\) to load the file to send.

![](https://github.com/ipfs/mobile-design-guidelines/tree/c30d2d6a1b009d38d16b7babc146d1c1f8604f13/.gitbook/assets/sharedrop-5%20%281%29.png)

The device sending the file has to confirm the share.

![](../../.gitbook/assets/sharedrop-6.png)

There is then a notification showing the device is waiting for the share to be accepted and transfer.

!\[\]\[image-7\]

On the receiving device the user then receives a notification to Decline or Save the file sent.

## Summary

* Web app only, although works in most mobile browsers
* Confusing avatars sometimes seem to reload differently making choosing shares confusing
* File transfer of a 2MB photo was instantaneous
* Would probably work better as a native app but very good that does not require any accounts or install to use
* Could be hard to use for some users to follow and understand what is going on in the sharing work flow

\[image-7\]: ../../.gitbook/assets/sharedrop-8.png

