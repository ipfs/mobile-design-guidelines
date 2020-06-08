# The user onboards confidently with minimal technical knowledge

When a user gets started with an app or service using IPFS, they shouldn't have to need to know they are. They should know IPFS works and provides a better way of handling data.

## What we found out in research

* Setting up accounts on P2P apps often requires additional security measures which many users might be unfamiliar with such as [long seed phrases](/application-survey/application-survey/manyverse)
* Onboarding is difficult to make [quick and informative](application-survey/application-survey/manyverse) at the same time

## Design considerations

* Users already have lots of accounts so let them try the app without having to have another one
* Try to reduce barriers to entry as much as possible by giving quick start options they can configure later
* Always show the user what they are signing up for when taking shortcuts 
* Put settings modifications last and only steer experts in that direction

### Who is the user and what are their needs

NGO worker concerned with censorship and privacy concerns who needs to send files to people

## Putting it into practice

### User downloads and installs app

To use the App X the user needs to first download and install it on their smartphone. This is typically done through an app store, but could on some platforms \(Android\) also be with a downloaded file.

### The app is opened for first time and learns what it does

When first opening App X the user sees quick messaging about what the app does. This is followed on the second paginated screen by information about how it does that with IPFS.

The user can skip the intro by tapping `Get started` or logging in if they already have an account.

There is also an option for the user to open a modal explaining the benefits of having an account with App X.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/GettingStarted-1.png)

> **Design consideration**
>
> Users already have lots of accounts so let them try the app without having to have another one

### The user chooses basic privacy settings

After clicking `Get started`, the user has two preset options for network and security settings.

They choose Basic. A confirmation screen which shows them all the settings now configured for them.

At this point they also have the option to create an account. This would provide them additional features, for example a file history or versions. They can create an account by entering `Login` and `Password` and tapping `Sign up`.

The user also has the option to continue to use a more limited version of the app. To do so they tap `Continue without account` which will use the Basic settings they have chosen.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/GettingStarted-2.png)

> **Design consideration**
>
> Try to reduce barriers to entry as much as possible by giving quick start options

### They decide to not create an account until later

The user decided they want to try the app before signing up for an account becasue of privacy concerns. They know the easiest way to approach internet privacy is to have as little online identity as they can. They're not sure if they need the extra features and are more interested in testing the app out.

They can't share anything on the IPFS network without first putting it on IFPS. They're given a number options such as sharing a photo, video or other sort of file.

![](https://raw.githubusercontent.com/ipfs/mobile-design-guidelines/master/.gitbook/assets/GettingStarted-3.png)

