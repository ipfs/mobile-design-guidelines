# The user shares a file through another app

What users do not need is another app or service to do things they are already doing on their smartphones. Discovering and installing a new app is already a barrier to entry. A bigger barrier is managing another application to message or transfer data. This is especially the case when the user usually does it another way.

### What we found out in research

* [Users](user-research/interviews/potential-users) are often hesitant to use new apps to do the things that
* [Early adopters](user-research/interviews/early-adopters) are increasingly interested in not using cloud services to share files

### Design considerations

* Try to use the existing mobile OS and its conventions as much as possible
* If your app has contacts stored already, utilise these for sharing as much as possible
* Prioritise frequent contacts
* Show a confirmation with CID, link or hash of the file

### Who is the user and what are their needs

Student in early 20's who wants to send files directly between smartphones not necessarily on the same operating system without having to upload it somewhere

### Putting it into practice

#### Open a photo in gallery or other file browser app on their smartphone

One very common user pattern is to share a file from the native application. This is especially the case with photos which are easier to view in photo gallery apps.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ShareFile-1.png)

#### Open share menu

Major mobile operating systems such as iOS and Android have contextual share menus which work across the OS. App X would also be available for instance in this bottom sheet menu. The user taps this button to share with App X.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ShareFile-2.png)

> **Design consideration**
>
> Try to use the existing mobile OS and its conventions as much as possible

#### Select and share through App X

A modal opens in the photo gallery app which shows the different share options for App X.

The user taps `Email` and enters in an email of a friend and then taps `Add to network and send link`.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ShareFile-3.png)

> **Design consideration**
>
> If your app has contacts stored already, utilise these for sharing as much as possible and prioritise frequent contacts

#### Confirmation to user showing CID link and button to open App X

The CID of the image that has been added to the IPFS network is emailed to the entered email address and the user is shown a confirmation with the hash and a link to open the image in App X.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/ShareFile-4.png)

> **Design consideration**
>
> Show a confirmation with CID, link or hash of the file

