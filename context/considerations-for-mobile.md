# Considerations for Mobile

There are couple of main areas of consideration when researching IPFS: mobile browsers, mobile battery life , mobile signal and data capabilities and privacy/identity. Throughout the research we layout these considerations as well as some questions to bear in mind as we explore IPFS for mobile.

## Mobile browsers‌

One extenuating factor with browsers on mobile devices is their limited feature set. While browsers on the desktop are often already feature-rich, they also feature extensions and add-ons, many of which enable additional features not readily available in the base install. This lack is vital for several reasons, first of which is that it means that anyone developing p2p applications, can not easily do this through the pre-installed browsers such as Chrome \(Android\) and Safari \(iOS\) on the two most dominant platforms.

The mobile ecosystem has developed over the past decade to be app-centric. This centricity means that when developing for mobile in general, much effort is geared towards developing native apps. However, this trend shows some pushback recently with movement away from native apps and trying to make the mobile web more powerful, such as through Progressive Web Apps \(PWAs\). This trend is because it allows developers to write one \(web\) application instead of two native applications on continually changing standards and feature sets for a continually evolving handset landscape.

### Questions

* Will mobile web development frameworks advance enough and gain enough support to allow P2P to work in a mobile browser?
* Will users make the switch from native apps to using their mobile browsers? Will the growth of mobile browsers help or hinder this?

## Battery life and power

It is clear that battery life is an issue with mobile devices; however, how much of an issue is very relative. Often, battery power is monitored by users only when low, and many mobile users now carry additional battery packs when on the go or where otherwise not able to charge readily. Additionally, each new mobile device release comes with extended and more robust battery life, decreasing the amount of importance this may have for users. This increase is also true across the spectrum of demographics and markets globally. Now in the emerging markets, charging is less of an issue as it may have once been, save for extremely rural areas and conflict or disaster scenarios.

While the development of P2P applications for mobile is nascent, development has already run into issues with battery life. Keeping a P2P node up on the phone can drain a mobile battery relatively quick. Therefore, battery life will increasingly be an issue with IPFS on mobile as it becomes more commonplace. Though essential to different degrees, power is still an important variable to consider that is mostly not an issue on the desktop or in IPFS desktop use cases.

### Questions

* Can notifications be used more appropriately to battery life and particular use cases such as sharing files over IPFS on mobile?
* Is there a way for IPFS applications to throttle use depending on mobile user context?

## Connectivity, bandwidth and signal

Connectivity on mobile is an obvious secondary requirement for IPFS mobile. However, the connectivity landscape is broad and varied, which is both an opportunity and significant consideration and development challenge for teams.

IPFS for mobile can take advantage of development in many types of connectivity. First is the data connection on just about every handset via 3G, 4G, LTE and now 5G. This mobile data connection allows handsets to maintain often good data speeds while the user is on the move. Second, almost all modern handsets have wi-fi capabilities. These connectivity options mean that connectivity switches depending on which mode, wi-fi or mobile data, is available. This switching also leads to the user problem of this not necessarily going to the connection that is faster or more stable. Often the user is then left to decide or guess and test and then switch connections manually. Third, IPFS for mobile also allows for Bluetooth connectivity, not commonly used as much anymore directly, but perhaps could be again in decentralised sharing use cases.

It is important to note that wi-fi and Bluetooth do not exclusively rely on a centralised connection for data transport. This connection then means that once devices are networked or connected via wi-fi or Bluetooth, they can connect directly to one another without having to use the centralised Internet at all.

### Questions

* Are there any ways in development to make network switching seamless for the user?
* Is it possible to design interactions to facilitate or even encourage more local networking?

## Privacy, security and identity

One of the most significant concerns in many areas of computing and Internet use is that of privacy and its implications for identity on networks. Although users in many markets not focused on banking and transactions might not have the same level of concern for identity theft, hacking or having funds stolen, there is still an issue. Applications and data on IPFS on mobile would diminish this as they are decentralised. For the user, this means that identities, keys and passwords not necessarily held on a central server able to be hacked, lost or stolen, are distributed or held privately. This distribution does force on the user additional responsibilities in configuration and storage and can lead to other issues such as losing unrecoverable keys.

### Questions

* What is the landscape of apps and platforms to facilitate methods like federated identity to make IPFS on mobile a reality for most users?
* What is the user need for mobile identity and P2P?

