# TSSOP - Distributed Social Network and Micro Blogging Project

## The Idea (Version 0.2.0)

Slowly also the slowest ones understands the danger of huge companies collecting as much data as possible about humans using the net. The train already left in direction of more privacy, sharing data only with selected people, avoiding data miners and companies making 97% of their money out of knowing as much as possible about users. As usual the smart ones are first and already moving to <a href=”http://localhost:1313/2018-03-12-riot-im-messenger-kurzanleitung-fuer-benutze-updated/” target=”_blank”>Riot Messenger</a>, <a href="https://kmj.at/2018-04-04-ein-weiterer-schritt-in-eine-dezentrale-zukunft-ist-getan/" target="_blank">Mastodon Micro Blogging</a>, self hosted clouds with e.g. OwnCloud/NextCloud and much more. I don't mention E-Mail servers because I assume all smart ones runs their self hosted server. It is more than stupid to let foreigners read, analyze or sell your valuable data. <a href="https://torproject.org" target="_blank">Tor</a> is used as browser by more and more people to protect their privacy and avoid tracking. 

I was really surprised to see the train already is kinda fast and even smart governments moving on to privacy protecting, encrypted, secure, decentralized Open Source solutions. **The french government moves from a proprietary – let foreigners and people you don’t know read and analyze all – solution to Matrix:** https://matrix.org/blog/2018/04/26/matrix-and-riot-confirmed-as-the-basis-for-frances-secure-instant-messenger-app/ . I am very sure there are more governments and organizations in urgent need for a change out there.

**Community is missing a tool to replace their social network without the hassles of setting up servers, or registering at some other service. Meanwhile even mobile devices are strong enough to handle serving the users profile, blog and messages via the Tor network.**

<p>&nbsp;</p>
<img src="https://kmj.at/images/tssop/TSSOP-20180315.jpg" border="0">
<p>&nbsp;</p>

The idea is to make it very easy for non-techie users. Download and start the Software, enter your “Display Name” and you are on. Tor hidden service onion address and everything else must be created fully auto without user intervention. Non-techies have no idea of certificates and other stuff, they will leave in minutes if they don’t understand what to do.

Connection to others using QR codes or typing the onion address and the connection is established.

Non-techies only need to know that all of their content is hold encrypted on their device, no commercial provider is involved to store all of their sensitive data. Furthermore all communication is encrypted and information is shared peer-to-peer only between the devices communicating. Using the Tor network even their IP address is hidden to the devices they are communicating with. 

**Privacy as needed by people even they don’t understand the tech details.** 

### Short Intro:
- distributed Social Network without the need of servers, using Tor Hidden Services
- maximum privacy because p2p connection between devices, no central server
- visitors connects to .onion address of the device  to remain as much privacy as possible
- every user keeps his data local. Everything is encrypted with the users passphrase.
- multi device sync and auto fail over. One device is master, others are backup. Content is synced over all devices via Tor.

### Feature Ideas
- profile with permission system who can see which parts of it
- blog with permission system who can see which parts of it
- friends with permission system. Allow friendship, subscription or both
- 1:1 end-to-end encrypted Messaging
- configurable timeline to select other blogs, profiles and their appearance
- auto delete of older blog posts and messages. Configurable setting of purge time.

### Tech
- all communication is encrypted using the Tor network
- messaging is furthermore end-to-end encrypted
- local storage on device is encrypted with user passphrase
- .onion addresses are auto generated on setup of first device
- additional devices syncs against the primary device.
- in case of failure of this device a backup device takes over without user intervention. If device comes up again, primary makes itself primary again.

### Requirements for Decentralization/Fediverse to grow (20180528)

We definitely need a single static binary, letting non-techies run instances of TSSOP. Access and synchronisation via TOR should be included within this binary so users have to install only one file!

- **why one binary:** non-techies are not in the position to setup servers. They will always overload public servers and avoid installing an own instance/server. With a single binary they can run it on their PC or mobile device without any hassles. I assume Go or Rust would be the language to use. With Go it should be possible to develop one Software for Linux, Mac, Windows, Android and IOS.

- **why Tor:** Tor is able to offer hidden services, so even a mobile phone can serve public services using the youraddy.oonion address. This is not working with IP only. Tor itself is encrypted and anonymizing the users real IP. Adding self signed certs on top of it would add another layer of security.

I am 100% sure, this one binary solution is the only way we can get the masses on our new social network. A side effect is, that the network scales kinda easy without any problems.

### Availablity
- Desktop versions for Linux, Mac and Windows
- Apps for Android, IOS, PureOS (hoping Librem5 will make it to the market)

### Scalable
- normal user only have a few visitors and a mobile device +LTE should be able to handle the traffic
- users with high traffic requirements should run the desktop version as primary device to handle their traffic. There should be a way to fix this device as primary to not fail over to some mobile device.
- as soon as 5G enters the market there will be no normal users exceeding their available bandwidth.

### FOSS – Free Open Source Software
I really believe in Open Source Software projects and TSSOP should be Open Source too.

## Next steps

- finalizing the idea
- team building to get the right people together. Software development, security, interface design and much more is to do. 

## Team Building

Team building to get the right people together. Software development, security, interface design and much more is to do. Actually we have problems to get people together. 

**PLEASE SPREAD THE WORD – TSSOP URGENTLY NEEDS COOL PEOPLE TO START ASAP**

Actually I decided to setup a community and different rooms inside the Riot.IM Matrix to have all communication in one place. CTS GMBH has donated us space inside their matrix.ctseuro.com server. Riot works great on all devces and is fully free and Open Source. Check it out at <a href="https://riot.im" target="_blank">Riot.IM</a> and register a free account there if you are not on Riot till now.

I am looking to meet developers, experienced with Tor, Encryption, Go, Rust, Linux, Mac OSX, Windows and mobile devices. For sure all people with interest in helping things getting started are very welcome!

Love to hear from you on Riot.IM. Looking forward to discuss the idea!

Available via Riot.IM as **@karl:matrix.ctseuro.com** or
via Mastodon as **https://mastodon.ctseuro.com/@kmj**.

### Team Status:

- Karl (Austria) - over 30 years IT experience @karl:matrix.ctseuro.com
- Markus (Germany) - over 15 years IT experience @markus:matrix.ctseuro.com


## Stage: 

- Idea / Planing
- very detailed idea to change the world of social media!

## Statusupdates

- 20180316 added Github <a href="https://github.com/tssop/" target="_blank">github.com/tssop/</a>
- 20180528 added ideas about Go and Single Binary for non-techies, changed some text to explain the project more in deep

<img src="https://kmj.at/images/tssop/TSSOP-20180315.jpg" border="0">
