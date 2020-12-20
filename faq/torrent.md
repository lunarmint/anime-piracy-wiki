# **A Complete Guide To Torrenting**

---
&nbsp;

## **► Basics**
---
&nbsp;

### **Why should I use torrents?**

To most people, streaming sites seem easy and torrents too complicated. But, a properly automated system with torrents is just as simple and allows for a ton of flexibility. Use torrents if you want - 

* The absolute best quality
* Smaller sizes at the same quality as streaming for low data caps
* An option to pick and customize the kind of subtitles you want to watch
* To be able to find anything you want to watch without hopping through different sites or begging on places like r/animepiracy

&nbsp;

### **What is torrenting?**

BitTorrent is a protocol for P2P file sharing. Peer-to-peer means that files are not transferred from a single, centralized server to your computer, but rather by a decentralised network of peers consisting of users like yourself.

The process of sharing files through torrents is completely legal. Transferring copyright infringing files may be illegal depending on your local laws and whether you get caught.Copyright organizations scrape lists of peers, and send takedown notices to the internet service provider of users participating in the swarms of files that are under copyright. In some jurisdictions, copyright holders may launch lawsuits against uploaders or downloaders for infringement. DMCA notices are much more common for Movies/TV shows than Anime. 

The solution is to use a [VPN](faq-vpn) or [seedbox]() or [private trackers]() if your country or isp enforces this

To get started, grab a torrent client from the list below

&nbsp;

### **Torrent Clients**

This is the program where you load torrents, it connects to other peers/seeds and downloads the files. 

Recommended clients - 

**PC:**

* [qBittorrent](https://www.qbittorrent.org/download.php) (Recommended) - Open-source torrent client. Has a built-in search feature that searches popular public trackers through plugins, and can also be connected with [Jackett](https://github.com/Jackett/Jackett)
* [Transmission](https://transmissionbt.com/about/) - Simple and lightweight open-source torrent client
* [Deluge](https://dev.deluge-torrent.org/wiki/Download) - Open-source torrent client
* [rTorrent](https://github.com/rakshasa/rtorrent) - Terminal-based torrent client for linux
* [ruTorrent for rTorrent](https://github.com/Novik/ruTorrent) - Web management UI for rtorrent
* [Flood for rTorrent](https://github.com/Flood-UI/flood) - Sleek web management UI for rtorrent

* **[Windows]** [uTorrent 2.2.1 Build 25302](http://web.archive.org/web/2011*/http://download.utorrent.com/2.2.1/utorrent.exe) - If you're still set on using uTorrent, this is a stable old build of uTorrent, before it turned to crap and had malware added. It was released on May 18, 2011. Set `net.discoverable` to False in settings and disable the Web GUI to mitigate security vulnerabilities that were later discovered. You can grab the installer from the wayback machine, as it has it cached. Just navigate to a close date past the release date noted earlier. You can check which version you have downloaded by checking the file's properties, in the details tab.

Note: Bittorrent Inc. has bundled malware (a bitcoin miner) into [uTorrent in the past](https://www.trustedreviews.com/news/utorrent-silently-installing-bundled-bitcoin-mining-software-2931825) - it is not trustworthy. Bittorrent (the torrent client) is owned by the same company.

Bitlord torrent client [is malware.](https://www.reddit.com/r/torrents/comments/1yb8kf/warning_do_not_download_bitlord_it_has_major/)

**Android:**

* [LibreTorrent](https://play.google.com/store/apps/details?id=org.proninyaroslav.libretorrent) - Ad-free, open-source torrent client for Android.

* [Flud](https://play.google.com/store/apps/details?id=com.delphicoder.flud) - Popular torrent client for Android.

* [Transdrone](https://f-droid.org/packages/org.transdroid.full/) - Remote torrent management app for your torrent client running on your main PC. Supports several torrent clients

* [nzb360](https://play.google.com/store/apps/details?id=com.kevinforeman.nzb360) - Remote torrent management app with support for managing Sonarr / Radarr / Lidarr / Bazarr / Sickbeard / Couchpotato / Headphones

&nbsp;

### **How do I torrent?**

First, you need to find a torrent file or magnet link for the content you want to download. You'll find that on websites like nyaa. These sites are also called [trackers]()

A .torrent file can be added to the client by simply opening by double clicking or browsing to the location and opening it from within the client.

A magnet link can be pasted into the client or by clicking on it within the browser. It'll prompt for allowing your torrent client to open, check always allow on that for an easier experience.

Most clients will begin leeching/downloading when you add the torrent, and being seeding/uploading once just a few pieces have downloaded, then will continue seeding after the torrent finishes downloading.

**Important:** After the torrent is done downloading, you allow it to **seed** at least for a while, ideally forever. Seeding is the way you give back to the swarm you leech from. The ratio is your upload divided by download. A ratio of 1 implies that you seeded as much as you leeched. Further, you may be seeding parallelly as you download, as you don't need the whole file to seed.

Don't worry if your upload speed is zero, it just means that you are available to seed, but there might be other peers with faster connections that are uploading to leechers.

&nbsp;

## **► Advanced**
---
&nbsp;

### **qBittorrent Features**

They're all available in most clients, I'm just using qBit as an example. The functionality is broadly divided into 3 tabs visible in the top bar - Transfers, Search and RSS. If they aren't visible, you can enable them from the View menu.

**Transfers** - This is where you can see all the torrents, which can be filtered by status, category and tags in the left pane. Categories and tags can be updated by selecting the torrents > right click.

**Search** - This is one of the most powerful features of qBittorrent. You need to enable search plugins by clicking the button at bottom left > check for updates. That will populate the list with some of the common trackers. Unfortunately, nyaa is not one of the default plugins, but it's available at http://plugins.qbittorrent.org with instructions on how to install them.

A better method is to add multiple trackers through the default search plugin called Jackett. Jackett is a separate program which has to be installed and can be configured with most private and public trackers, this plugin allows qBittorrent to search through Jackett.

**RSS** - This is the simplest way of automating downloads. It's easier to explain with an example, suppose you want to auto download any of the currently airing anime - 

1) Copy the rss feed link from nyaa or subsplease

2) Click "New Subscription" at top-left and paste the link, torrents will now show up in the middle pane.

3) Open RSS downloader (top right) and click the new rule button next to "Download Rules"

4) Give it any name and type the name of your anime in the field "Must Contain:"

5) (Optional) Set the category, save path and other settings

qBitorrent can be left running in the background, and it'll download the episode as soon as it comes out.

&nbsp;

### **Connectability**

The concepts of connectability and port forwarding are all about the first step of connecting to peers, once you're connected, no matter how, you'll get the same speeds. However, a properly configured setup increases the pool of potential peers to connect to. This won't make a difference with torrents that have hundreds of seeds, but can drastically increase speeds on torrents with less seeds. A torrent client will still work with closed ports.

**If your port is closed, you can only connect to those who have their port open.** If it's open, you can connect to everyone.

**Make sure to enable DHT and PEX in your torrent client, especially if you're using public torrents.**

The tracker is a server that gives you a list of peers to connect to. A few trackers are enough, please don't paste in huge tracker lists copied from random places, they don't help. Often, trackers aren't even needed when you have DHT/PEX enabled, though they do help with starting the process of finding more peers through PEX. If it's'a public torrent then all seeds/peers will find each other eventually using DHT/PEX regardless of any trackers.

&nbsp;

### **Port Forwarding**

Port forwarding is essential to make sure you are fully connectable to maximize your speeds and ability to connect to other peers in a swarm.

Your connection is assigned a public IP address by your ISP and your device is assigned a private/local IP address bu your router. On your computer, services which need to connect with other devices over any network run on a port. The IP address plus port number is it's identification, this combination can be used to access the service in the format IP:port.When you run the torrent client, it runs on a port on your computer's IP address, which is local and can only be accessed by devices connected to your home network. 

This port on your internal IP has to be forwarded/connected to the equivalent port on your external/public IP. Once that is done, anyone over the internet will be able to connect to your torrent client through that port on your public IP as the connection will be forwarded by your router to where the torrent client is running on your internal network. Note that this is completely safe.

The port used by your client can be found in Settings > Connection. It is usually a number above 10000 or so. (preferably [49152 or higher](https://en.wikipedia.org/wiki/Ephemeral_port), some ISPs rate limit lower port numbers). **This port number should not be port 80 or 6881-6889.**

Use http://www.canyouseeme.org to check if the port of your torrent client is forwarded. Use http://portforward.com for instructions on how to port forward for your router. If setting up a port forward in your network router do not use port triggering. Optionally, in your ISP router/modem, disable all things resembling flood protection, DDoS protection, traffic shaping, QOS etc.

&nbsp;

### **What is a seedbox?**

A seedbox is a server, a computer in a datacenter with high bandwidth/speeds. It's commonly used as a service that leeches torrents for you and provides the files in a direct download format, or uploads them to a cloud drive of your choice. They also seed the torrents, and have high upload speed, and so they're used by Private Tracker users. Since the seedbox has a high upload speed compared to regular peers in the swarm, it is more likely to be chosen to upload pieces. Typical advantages:

  - Faster download speeds, but obviously still limited to your own speed.
  - Avoiding copyright/dmca problems.
  - Seeding - A seedbox is on 24 hours seeding your torrents at high speeds, that allows you to maintain a good ratio on private (and public) trackers.
  - Running your own VPN.
  - Lots of other automation/streaming solutions - plex, radarr, sonarr, etc.

Check out r/seedboxes for more information. They are geared towards private trackers so be sure to check for public tracker support and unlimited bandwidth with any seedbox provider.

&nbsp;

## **► Trackers**
---
&nbsp;

### Public

* Nyaa.si (mirror - meowinjapanese.cf)
* AnimeTosho - Scrapes public trackers, it's useful for getting only the subtitles from a torrent
* Anidex 
* Nyaa.net
* Rutracker (Russian)

In general, nyaa.si is your best option for everything

Refer to this [detailed guide]() for finding anime on nyaa and elsewhere. If you're in a rush, try searching for these terms on nyaa - 

* Erai-raws or Subsplease for seasonals

* Releases from [SeaSmoke's Anime Index](https://docs.google.com/spreadsheets/d/1emW2Zsb0gEtEHiub_YHpazvBd4lL4saxCwyPhbtxXYM/htmlview#) or [A Certain Fansubber's Index](https://docs.google.com/spreadsheets/d/1PJYwhjzLNPXV2X1np-S4rdZE4fb7pxp-QbHY1O0jH6Q/htmlview) for completed anime

&nbsp;

### Private

* AnimeBytes
* BakaBT 
* AnimeTorrents
* U2 (raws/bdmv)
* Skyeysnow (Chinese - open signup - raws/bdmv)

[This wiki page](https://wiki.installgentoo.com/index.php/Private_trackers), originally written for 4chan's /g/ board, is a very good resource that explains private trackers in detail. Note that some of the information is out of date (for example, it states that applications are a viable path into AnimeBytes when they haven't accepted applications in years and probably never will again) but it's still a great resource.

There's also an updated [FAQ](https://pastebin.com/GWdYH33j) and more which you can find on the /g/ptg thread

&nbsp;

### **How do I join Private Trackers?**

Typically by open signups, interviews, applications, recruitment and user invites. The ways to get into common private anime trackers are given below. Check out the resources linked above for more.

AnimeTorrents (AnT/AnimeZ) - usually has open signups once or twice per year, typically towards the end of the year around the holiday season. /r/opensignups is a good resource to figure out when they're open. AnT also allows users to buy invites for their friends with bonus points but the page for sending invites has been broken for years and won't be fixed anytime soon.

BakaBT (BBT) - only allows new registrations from users who successfully pass an interview via IRC. The interview is mostly about the rules and information that you can find on their wiki.

U2 - used to recruit on select Chinese trackers in the past and also has user invites. You should not consider user invites to be a valid path to U2.

AnimeBytes (AB) - recruits from select few top tier trackers and also has user invites. Please note that:

- RED is the only entry level tracker that AB recruits on and it is *extremely* difficult to survive on RED. The AB recruitment thread on RED requires you to be at least at power user (2 week old account, uploaded at least 5 torrents, 25GB uploaded, and >0.65 ratio) and your account must be at least 12 months old. If you were able to pass the RED IRC interview today, you would still have to wait over a year to join AB.
  
- Users are responsible for who they invite on AB. The actions of the invitee can result in a ban for the inviter, as well as the entire invite tree, which results in people being unwilling to share invites. You should not consider user invites to be a valid path to AB.

&nbsp;

## **► Glossary**
---
&nbsp;

- Peer: any person who is uploading/downloading a torrent.

- Swarm: the entire set of peers.

- Seed - a peer who has finished downloading the torrent and is now only uploading it to other peers

- Leech - a peer who is still downloading OR a user who downloads more than they upload

- Seeding - uploading to other peers in the swarm

- Leeching - downloading from other peers in the swarm

- Ratio - the number of bytes of data you've seeded to others divided by the number of bytes of data you've downloaded from others. If you download a 2GB movie, and you've seeded 1.5GB, your ratio on that torrent is 0.75 (1.5/2.0). Most clients will also display somewhere the overall ratio of all torrents in the client. If you join a private tracker, you'll likely have to maintain a minimum ratio to retain membership.

- Tracker - a server that clients talk to to get up-to-date lists of peers from the swarm. Each torrent may have zero, one, or many trackers. Private trackers are websites that run their own private tracker. All torrents from a private tracker website will use only that private tracker.

- Trackerless torrent - a torrent that doesn't use any trackers. Peers share lists of peers with each other instead.

- DHT - distributed hash table, the basis of trackerless torrents. Basically it's a giant table that, as the name implies, is distributed among all torrent clients. This table basically functions like a giant distributed tracker of all torrents that use DHT

- PEX - peer exchange. This protocol allows peers on the same torrent to exchange lists of peers with each other. It's not as powerful as DHT because it can't be used to join a new trackerless torrent; you have to know which peers to ask before you can ask.

- Torrent file - a small file with a .torrent extension that you download to begin torrenting. Contains metadata about the torrent (checksum, list of files and their sizes, etc).

- Magnet link - a link containing at minimum the checksum of the torrent. May also contain the torrent name and/or one or more trackers. Since the magnet link doesn't contain torrent metadata, the .torrent file must be downloaded from the swarm first before the actual torrent can begin. Without any trackers, a magnet link requires DHT to find initial peers and begin downloading the .torrent file.

- Checksum/Hash - a fixed-length value that is calculated based on all of the data in the complete torrent that is intended to be unique to the specific torrent. Think of it like the torrent's unique ID. Used to identify the torrent to trackers and DHT

&nbsp;

## **► Related Subreddits**
---
&nbsp;

/r/trackers - For discussion of public and private torrent trackers. No requests of specific pirated titles.

/r/Invites - Request and offer invites for private trackers that allow for invites to be distributed through such means.

/r/OpenSignups - Announcements of private trackers that have opened up registration or applications. opentrackers.org is another great resource

/r/VPN - Discussion of VPNs

/r/VPNTorrents - Discussion of VPNs for the purpose of torrenting

/r/torrents - For torrents dicussion and news