# User plays a shared media file without wifi or mobile network

Unlike cloud services like Dropbox and Google Drive, IPFS doesn't need centralised Internet access to transfer files. The files can be transferred direct device to device. This is because they don't need to first go through the Internet to a central server.

## What we found out in research

* QR codes are a quick and easy way of [sharing data and files](application-survey/application-survey/sharedrop.io)
* The user should be aware of [where the files are](user-research/interviews/potential-users)

## Design considerations

* Display relevant file information such as name, file size and type
* Present the user their network status if it affects their abilities with the app
* Show many methods of sharing, including by QR code, together in the same place
* Don't assume the user knows what to do with a QR code
* If allowing the user to publish or un-publish, notify them of the conditions, such as it expiring after a certain time

## Who is the user and what are their needs

A person who commutes long distances to and from work who often loses signal \(4G, LTE, etc.\) when on the train. They're interested in being able to have everything work if connected or not by default.

## Putting it into practice

### Another App X user shared a file while not connected to wifi or mobile data

The user opens App X to see a video file another App X user shared before.

There is no wifi or data connection available. Because they were both using an app built on IPFS, the other App X user was able to send them the video over Bluetooth.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/Offline-1.png)

> **Design consideration**
>
> Present the user their network status if it affects their abilities with the app

### The user previews the media file

The user can view all files they've had access to. They choose to watch the shared video they have a complete and always available copy of.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/Offline-2.png)

> **Design consideration**
>
> Display relevant file information such as name, file size and type

### The user shares the video with another App X user

The user wants to re-share the video to another App X user. Since they are sitting right next to one another he decides the quickest way to share it is to show the QR code. The friend then scans the the code which opens the link and the video for them in App X.

The user's app then notifies them that their friend accessed the video.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/Offline-3.png)

> **Design consideration**
>
> Show many methods of sharing, including by QR code, together in the same place

### Unpublishing the video

After they've shared the video, the user decides they don't want to continue publishing the file. The video was set to `Publish` by default in their settings. They deselect `Publish` in the options bottom sheet menu.

The screen displays information that their copy of the video will then expire. The user choses in their settings how long it takes for un-published files to expire and disappear from their App X. In this case one day.

Other people with a copy of the video need to continue publishing the video for others to be able to access it.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/Offline-4.png)

> **Design consideration**
>
> If allowing the user to publish or un-publish, notify them of the conditions, such as it expiring after a certain time

