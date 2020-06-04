# Give control over data

Mobile apps and services should help manage files. They can do this by respecting the needs users may have with availability, discoverability and persistence. This also includes helping them know they have a full and complete copy, even offline, of the files.

### What we learned in the research

* Many users think the final location of the file isn't that important as long as they have a copy
* Organisation and management of files is very important while sharing
* Users worry about links to files on cloud services as they only work for a certain amount of time
* There are concerns about syncing and trusting a connection especially with big files
* There is generally the lack of ability to manually push sync
* Some users feel versioning makes some cloud services such as Dropbox indispensable

### Patterns

#### Assure that the files are safe

Users are more concerned with their files being safe rather than where they are. Safe in most cases means that files are accessible and there are controls on who can get to them.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Have file level modification controls | Hide how the user can control file permissions |
| Make files viewable so the user can make sure they are there | Hide information about the file such as size and type |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/GiveControlOverData-1.png)

_Users should have easily accessible file information and controls, for instance through individual options_

#### Be clear about who has access to what

A great deal of the concern about user's data is about who has access to what. When managing access on particular files and groups of files, the user needs to sure what is going on so they can understand the risk better.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Create simple ways of understanding what access to a particular file means | Over-complicate permissions |
| Show that a file or group of files can be accessed by someone else | Assume the user understands the sharing defaults |
| Have ways of making a file or group of files inaccessible | Hide sharing controls |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/GiveControlOverData-2.png)

_Files should indicate what their sharing status is_

#### Give the option to use classic file and folder organisation

While innovative organisational schemes for file management are appreciated by many, for many more they are confusing.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Allow the user to see all their files by default | Auto-organise files and folders for users |
| Give the user simple views of file and folder lists | Only give the user the option to view the files by thumbnail |
| Follow establish file and folder display conventions | Use file viewing methods from different mobile OS's which might confuse users |
| Have the app handle links and hashes automatically | Tell the user if they modify files they have to fix links themselves |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/GiveControlOverData-3.png)

_The user should be able to easily filter different views of the file list, for instance by all, starred or shared._

