# Make privacy work for the user

There is no shortage of concern about privacy and security for all levels of users, from expert to novice. Most users worry about their data in some way, shape or form. This worry though is generally related to how much they have invested in and value their online life. What users want is assurance that they have some level of privacy or security so their data and files are safe.

### What we learned in the research

* People consider privacy and the ability to manage a secure identity a right
* Security and privacy is important to users, but requires a lot of nuance to not make it overwhelming for the user
* Many times users are concerned about privacy and security but don’t know if they are handling it properly
* Identity management is critical but thought of as a challenging and a chore, so often ignored
* Users worry about managing permissions on files and folders
* Security and granular permissions are an issue and requires a lot of work and paying attention
* Most users already have multiple accounts with differing levels of security
* Digital IDs are complicated and easy at first but very complex when people forget or things go wrong
* There is a need to provide information on possible safety or legality issues

### Patterns

#### Have a default starter privacy setting or mode

Users need control to be approachable and considered safe enough for a new user. It can then be more complicated as they better understand what they're doing.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Tell users what possible risks the app presents for their data and how it will take care of it | Use complicated and overwhelming terminology such as "threat" and "intrusion" with new users |
| Provide a safe mode for new users to get started | When first presenting privacy options to the user, show a long list of controls |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/MakePrivacy-1.png)

_Make privacy setup during onboarding as quick and painless as possible while providing options. In this case, Advanced could take the user to an option screen with detailed controls._

#### Understand the user has many other accounts on many other services

Almost all levels of users have many online identities. For instance, they have separate ones for work and for home as an elementary safety precaution. This is to separate different parts of their digital lives. Mobile apps built on IPFS should not confuse this or make the handling of this worse.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Provide account-free use or single sign-on when possible | Force the user to have an account if it isn't really necessary |
| Allow users to switch accounts easily if they have them | Obscure account switching features |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/MakePrivacy-2.png)

_Give the user the default option to not have an account if not necessary_

#### Be clear about the security methods and what is involved

Online security is an ever evolving landscape and new measures and ways of handling it are always being introduced. This often results in new apps and services introducing new ways of handling privacy and security users may not be familiar with. This creates additional barriers to entry and use.

IPFS encrypts data to the outside world, but not on the network. To encrypt data on IPFS, additional encyption often needs to be introduced, such as cryptographic keys to handle accounts.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Explain why certain security methods are required | Use public and private keys unless necessary |
| Hide long hashes and strings while allowing it to be viewable as an option | Require extremely long \(ex. 48 words\) recovery or seed phrases to generate keys |
| Clearly say when content is visible to the IPFS network | Hide the fact that IPFS exposes content within the network |

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/MakePrivacy-3.png)

_Tell the user what a key is how it works if you need to use them_

#### Give account fall backs

Part of the concern with accounts is what happens when things go wrong. Mobile apps and services using IPFS should be aware of this and provide alternate ways for users to safely get to their accounts if they forget passwords and keys.

| ✅ Do | 🚫 Don't |
| :--- | :--- |
| Allow the option to have alternate emails and other ways of authenticating | Require the user maintain and generate private keys with no additional help |
| Give the user a way to view recovery phrases | Assume a user understands the implications with recovery phrases |

