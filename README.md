# TSSOP - Distributed Social Network and Micro Blogging Project

## The Idea (Version 0.1)

Slowly also the slowest ones understands the danger of huge companies collecting as much data as possible about humans using the net. The train already left in direction of more privacy, sharing data only with selected people, avoiding data miners and companies making 97% of their money out of knowing as much as possible about users. As usual the smart ones are first and already moving to <a href=”https://kmj.at/2018-03-12-riot-im-messenger-kurzanleitung-fuer-benutze-updated/” target=”_blank”>Riot Messenger</a>, Mastodon Micro Blogging, self hosted clouds with e.g. OwnCloud and much more. 
Community is missing a tool to replace their social network without the hassles of setting up servers, or registering at some other service. Meanwhile even mobile devices are strong enough to handle service the users profile, blog and messages via the Tor network. 
The idea is to make it very easy for non techie users. Download and start the Software, enter your “Display Name” and you are on. Tor hidden service onion address and everything else must be created fully auto without user intervention. Non techie have no idea of certificates and other stuff, they will leave in minutes if they don’t understand what to do.
Connection to others using QR codes or typing the onion address and the connection is established.
Non techies only need to know that all of their content is hold encrypted on their device, no commercial provider is involved to store all of their sensitive data. Furthermore all communication is encrypted and information is shared peer-to-peer only between the devices communicating. Using the Tor network even their IP address is hidden to the devices they are communicating with. 
Privacy as needed by people even they don’t understand the tech details. 



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

### Availablity
- Desktop versions for Linux, Mac and Windows
- Apps for Android, IOS, PureOS (hoping Librem5 will make it to the market)

### Scalable
- normal user only have a few visitors and a mobile device +LTE should be able to handle the traffic
- users with high traffic requirements should run the desktop version as primary device to handle their traffic. There should be a way to fix this device as primary to not fail over to some mobile device.

### FOSS – Free Open Source Software
I really believe in Open Source Software projects and TSSOP should be Open Source too.

### Next steps
- finalizing the idea
- team building to get the right people together. Software development, security, interface design and much more is to do. 


Feel free to contact me on Riot to get invited to the TSSOP room. Looking forward to discuss the idea!
Available via Riot.IM as @karl:matrix.ctseuro.com .

Stage: Idea / Planing

