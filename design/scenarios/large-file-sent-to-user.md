# Large file sent to user

One of the largest issues with transferring files and messages is discoverability and security. A large part of security is the ability to control who and what can access files.

## What we found out in research

* File transfer not only requires [managing transfers](application-survey/application-survey/frostwire) but also files you already have
* File links should be [shown and able to be copied and if possible shown as QR codes](application-survey/application-survey/sharedrop.io)

## Design considerations

* Allow the user to be able to manage and delete files
* Show where the file is being stored and where it can be deleted
* Give the user preference options on where to store files, locally or otherwise
* Show confirmations to unreversible actions like deleting
* Make copying and sending CIDs as simple as possible for the user

## Who is the user and what are their needs

User working with large files and often having to work on-site with limited internet access

## Putting it into practice

### The user receives notification another App X user is sharing a file with them

The user receives notification they have received a message with a link to an image on App X. They recognise "JoeS" as their co-worker who sends them files regularly.

They then open the message link and App X opens begins downloading the shared image. At this point the user has the option to cancel the download.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/SentFile-1.png)

> **Design consideration**
>
> Allow the user to be able to manage, delete and show where files are stored

### Image downloaded in App X

The image is completely downloaded, the progress bar finishes and the user can then open it.

The user taps the image in the file list and goes to an image preview screen. The CID \(Content Identifier\) is then displayed. When tapped, it will copy to the clipboard. The user also has the option to share the image \(CID\) link through the share button at the top right. Other options, such as deleting or downloading the image are available from the options menu `...`.

The user also has the option to see the history of that file. They can get to that by tapping `History` at the bottom of the file view screen.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/SentFile-2.png)

### The user deletes the file

The user wants to delete the file from App X after viewing the file. They open the options menu `...` and tap `Delete from App X` and a confirmation modal appears.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/SentFile-3.png)

> **Design considerations**
>
> Give the user preference options on where to store files, locally or otherwise
>
> Show confirmations to unreversible actions like deleting

The user confirms deleting the file. As they had it synced with local storage, they know that the image is still on the phone but disappears from App X.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/SentFile-4.png)

