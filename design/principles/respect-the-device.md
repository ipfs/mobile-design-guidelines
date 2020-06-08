# Respect the device

## Respect the device

Apps and services for mobile aren't reformatted desktop apps. They need to take into account a host of different issues, from battery life to signal.

### What we learned in the research

* Many developers believe battery life and signal to be vital to end-users
* How vital batter is depends on the type of user and their context
* Users viewed battery and signal strength as important but only when it could be a problem
* Battery is less and less of an issue as they get better and external battery packs become more popular
* Offline-first design is a growing trend that requires special sensitivity to the user knowing when they are on and off line

### Patterns

#### Notify the user something might not finish because of the battery level

Battery life is an obvious and constant issue with all mobile users in any demographic. Battery life is less of an issue as smartphone batteries improve. But many user actions such as video and downloads can affect this.

Battery life is especially an issue with IPFS and P2P in general. The default of P2P is to connect to more and more peers. This, however, means there is a greater than average power drain.

Assume the user will at some point have issues with these.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Show a notification if the user is trying to transfer data and the battery is low | Indicate battery life issues with transfers and other actions to the user all the time |
| Show helpful, occasional and out of the way information to the user about their actions and affects on the battery | Show successive warnings |
| Check if the phone is on a power source already so connecting to a number of peers won't be an issue | Detect the battery level in the background all the time to notify the user |
| If possible, allow the user to choose how much battery drain is acceptable in exchange for peer connections | Set the app to automatically connect to as many peers as possible |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/RespectTheDevice-1.png)

_Notify the user when things might not work_

#### Show that actions like file sharing might take a long time or not work at all if there is not much signal

Signal is often thought of as not an issue until it's not there and apps built on IPFS can support this. It can provide and indicate offline capabilities as well as support data persistence. Apps that use IPFS should provide reassurance for the user for what is going on and what is possible. Thus, signal and mobile bandwidth should address for the specific context.

It should be noted that P2P technologies often try to create as many connections to peers as possible. This requires more bandwidth and more battery use. IPFS in mobile apps should be tuned to use fewer direct connections, and re-use high quality connections.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Indicate the user is offline | Notify the user that they need to go online for it to work |
| If on low bandwidth, show that a large file will take longer | Suggest offline capabilities so that the user needs to always be aware |
| If possible, allow the user to set bandwidth minimum amount and maximum peer count settings for transfers | Have default and unchangeable settings which favour maximum amounts of peers |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/RespectTheDevice-2.png)

_It is good to tell users they are offline so they will be aware of how the app will continue to work in a different manner_

#### If the user is on a data connection think about how to suggest time and cost involved

When a user wishes to transfer a large amount of files or data, they can't always rely on wifi. This is depsite being pervasive in many contexts.

Many advanced users have very high or no data limits on their monthly mobile data tariffs. But, many people still buy smaller and finite amounts of data at a time. With mobile apps using IPFS, the designer should be aware of technical and monetary restraints the user may have.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Detect the type of connection to provide support to the user | Show time to finish which may be inaccurate |
| Show a large amount of data might cost a lot to transfer | Force the user to switch modes of connection |
| Allow the user to pause and resume transfers | Hide the reason a transfer of data might have failed |
| Display estimated time to finish downloads when possible | Show progress bars without file size or time to finish information |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/RespectTheDevice-3.png)

_When they don't have full capacity, help the user understand the implications_

