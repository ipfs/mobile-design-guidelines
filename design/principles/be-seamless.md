# Be seamless

The user shouldn't necessarily know how they're connected, whether through wifi, bluetooth or otherwise. They should just feel confident that data is getting sent and received, not how.

## What we learned in the research

* P2P is understood by users as a concept relatively easily
* Users are not concerned are not with the type of connection but that it is stable, fast and not expensive
* Users prefer using integrated share functionality from other apps they use such as for photos
* Cloud services like Dropbox and AirDrop are considered very easy to use and intuitive for file sharing by many users
* Users might know of P2P but don't feel they need to be aware they are using it

## Patterns

### Don't require the user to manage their connections

When a user wants to transfer data on mobile, they are doing so because they need to do so then and there. If the app requires they manually change the connection to do so, they will be less likely to use the app.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Show data transfer subtly | Require users to switch from one connection type to another |
| Where possible, utilise the mobile OS to initiate transfer | Require files to be manually transferred to your app |
| Give the user the option to turn off automatic syncing | Sync without telling the user |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/BeSeamless-1.png)

_Ideally, your app or transfer method should be availble at the OS level, for instance in the menu that appears when sharing a file_

### Have as few settings as possible

Apps on IPFS should be simple and be able to work for users straight away when opening the app.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Provide simple, default settings to enable file and data transfer | Ask the user to understand and manage each transfer settings |
| Allow the user to set preferences for different types of connections, for instance only on wifi for files of a certain size | Limit what the user is able to do on a certain connection type or bandwidth limit |
| Allow the user to change settings from default ones later | Require the user to start a node when opening or using the app |

