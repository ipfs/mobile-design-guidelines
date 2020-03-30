# Considerations for mobile

### Mobile browsers

One extenuating factor with browsers on mobile devices is their limited feature set. While browsers on desktop are often already feature rich, they also feature extensions and add-ons, many of which enable additional features not readily available in the base install. This is important for a number of reasons, first of which is that it means that anyone developing p2p applications, can not easily do this through the pre-installed browsers such as Chrome (Android) and Safari (iOS) on the two most dominant platforms. The mobile ecosystem has developed as such over the past decade to be app-centric and this means that when developing for mobile in general, much effort is geared towards developing native apps. However, this trend shows some pushback recently with movement away from native apps and trying to make the mobile web more powerful, such as through Progressive Web Apps (PWAs). This is for the simple reason it allows developers to essentially write one (web) application rather two native applications on constantly changing standards and feature sets for a constantly changing handset landscape.

#### Questions

- Will mobile web development frameworks advance enough and gain enough support to allow P2P to work in a mobile browser?
- Will users make the switch from native apps to using their mobile browsers? Will the growth of mobile browsers help or hinder this?

### Battery life and power

It is clear that battery life and power is an issue with mobile devices, however how much of an issue is very relative. Often, battery power is monitored by users only when it is low, and many mobile users now carry additional battery packs when on the go, travelling or otherwise not able to readily charge. Additionally, each new release of mobile handsets comes with extended and more robust battery life, decreasing the amount of importance this may have for users. This is also true across the spectrum of demographics and markets globally, where now in the Global South, Android handsets are as common as elsewhere and charging less of an issue save for extreme rural areas and conflict or disaster scenarios.

While the development of P2P applications for mobile is nascent, development has already run into issues with battery life and keeping a P2P node up on a phone as this can drain a handset battery relatively quick. Therefore, it will be an increasing issue as P2P on mobile becomes more commonplace that battery life is taken into account. Likewise, though important to different degrees, power is still an important variable that is largely not an issue on the desktop.

#### Questions

- Can notifications be used more appropriately to batter life and particular use cases such as sharing and P2P scenarios?
- Is there a way for the P2P application to throttle use depending on mobile user context?

### Connectivity, bandwidth and signal

Connectivity on mobile is an obvious secondary requirement for IPFS Mobile, however, the connectivity landscape is broad and varied, both an opportunity and large consideration and development challenge for teams.

The advantage of P2P for mobile development is that mobile allows for many types of connectivity which can be taken advantage of. Firstly is the data connection on just about every handset via 3G, 4G, LTE and now 5G. This mobile data connection allows handsets to maintain often good data speeds while the user is on the move. Secondly almost all modern handsets have wifi capabilities. This then means that connectivity is switching depending on which mode, wifi or mobile data, is available. However, this also leads to the user problem of this automatic switching not necessarily going to the connection that is faster or more stable, meaning the user often has to decide or guess and then typically test and switch manually. Thirdly, P2P for mobile also allows for Bluetooth connectivity, not commonly used as much anymore, but perhaps could be again in P2P contexts.

It is important to note that wifi and bluetooth do not exclusively rely on a centralised connection for data transport, meaning once devices are networked or otherwise connected via wifi or bluetooth, they can connect directly to one another without having to use the Internet at all.

#### Questions

- Are there any ways in development to make network switching seamless for the user?
- Is it possible for interactions to be designed to facilitate or even encourage more local networking?

### Privacy and security

One of the greatest concerns in many areas of computing and Internet use is that of privacy. Although users in many markets not focused on banking and transactions might not have the same level of concern for identity theft, hacking or having funds stolen, there is still an issue. Applications and data on IPFS Mobile would diminish this as they are decentralised in nature. For the user, this means that identities, keys and passwords are not necessarily held on a central server that can be hacked, lost or stolen, but distributed or help privately and personally. This does impinge on the user additional responsibilities in configuration and storage and can lead to other issues such as unrecoverable keys being lost.

#### Questions

- What is the landscape of apps and platforms to facilitate methods like federated identity to make P2P for mobile a reality?
- What is the user need for mobile identity and P2P?