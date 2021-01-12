# **A Complete Guide To Torrenting**

---

&nbsp;

## **► Disclaimer**

---

&nbsp;

The process of sharing files through torrents is completely legal. Transferring copyright infringing files may be illegal depending on your local laws. Copyright organizations may scrape lists of peers, and send takedown notices to the internet service provider of users participating in the swarms of files that are under copyright. In some jurisdictions, copyright holders may start lawsuits against uploaders or downloaders for infringement.

**Note:** you may want to use a VPN or other proxy service to download torrents. You may be at risk of receiving a copyright infringement notice from your Internet Service Provider or a copyright body, and may risk having your internet limited or have the service revoked. 

&nbsp;

## **► Basics**

---

&nbsp;

### **Why should I use torrents?**

For many people, streaming services are more convenient to use. However, torrenting is fairly simple and allows for more flexibility. Some reasons to use torrents are:

- A range of qualities and sizes.


- Better subtitling and style options.


- Easier access to a larger variety of titles.


- Downloaded files for rewatching with no additional data usage.

&nbsp;

### **What is torrenting?**

The BitTorrent Protocol is an internet protocol for peer-to-peer file sharing. Peer-to-peer means that files are not transferred from a single, centralized server to your computer, but rather by a network of peers consisting of users like yourself.

Two ways to anonymize yourself is to use a [VPN](faq-vpn) or [seedbox]() if you are at risk of getting a notice from a copyright body.

&nbsp;

### **Torrent clients**

This is the program where you add torrents, connect to other peers, and download the files. 

|Name|Open-source|OS|Plugin support|Command Line|
:--|:--|:--|:--|:--|
|[qBitTorrent](https://www.qbittorrent.org/download.php)|Yes|Windows, Linux, macOS|No|Plugin|
|[Transmission](https://transmissionbt.com/download/)|Yes|Windows, Linux, macOS|Yes|Yes|
|[Deluge](https://dev.deluge-torrent.org/wiki/Download)|Yes|Windows, Linux, macOS|Yes|Yes|
|[rTorrent](https://github.com/rakshasa/rtorrent)|Yes|Linux|Yes|Yes (Only)|
|[LibreTorrent](https://play.google.com/store/apps/details?id=org.proninyaroslav.libretorrent)|Yes|Android|No|No|
|[Flud](https://play.google.com/store/apps/details?id=com.delphicoder.flud)|No|Android|No|No|

&nbsp;

**Some popular client plugins and mods for automation** - via /u/psbankar/ and /u/plissk3n/

- [Radarr](https://github.com/Radarr/Radarr): Manages your movie library.


- [Sonarr](https://github.com/Sonarr/Sonarr): Manages your TV library.


- [Lidarr](https://github.com/lidarr/Lidarr): Manages your music library.


- [Jackett](https://github.com/Jackett/Jackett): Meta indexer for torrent sites.


- [Traktarr](https://github.com/l3uddz/traktarr): Add content to Radarr/Sonarr from Trakt.tv.


- [Bazarr](https://github.com/morpheus65535/bazarr): Manages subtitles.


- [Syncarr](https://github.com/syncarr/syncarr): Syncs two Radarr/Sonarr/Lidarr instances.


- [Tdarr](https://github.com/HaveAGitGat/Tdarr): Automating media transcode/remux management and making sure your files are exactly how you need them to be in terms of codecs/streams/containers.


- [Readarr](https://github.com/Readarr/Readarr): Book, Magazine, Comics Ebook and Audiobook Manager and Automation.


- [Organizr](https://github.com/causefx/Organizr): Feature rich landing page.


- [Ombi](https://github.com/tidusjar/Ombi): User requests for media with Radarr/Sonarr/Lidarr integration.


- [Bobarr](https://github.com/iam4x/bobarr): The all-in-one alternative for Sonarr, Radarr, Jackett... with a VPN and running in docker.


- [Listrr](https://github.com/TheUltimateC0der/Listrr): With listrr.pro, you can create personalized trakt.tv lists for tv shows and movies with a variety of different filters, and use them with your ultimate PLEX setup.


- [Mylar3](https://github.com/mylar3/mylar3): Manages your comic library.


- [Wantarr](https://github.com/l3uddz/wantarr): CLI tool for Radarr/Sonarr.


- [Requestrr](https://github.com/darkalfx/requestrr):   Chatbot used to simplify using services like Sonarr/Radarr/Ombi via the use of chat!


- [Bonarr](https://github.com/bonarr/Bonarr):  Independent fork of Radarr reworked for automatically downloading adult movies via Usenet and BitTorrent.


- [Lazy Librarian](https://lazylibrarian.gitlab.io/): Books and Audiobooks manager and automation.


- [NzbHydra](https://github.com/theotherp/nzbhydra2):  Meta  search for newznab indexers and torznab trackers.


- [Pulsarr](https://github.com/roboticsound/Pulsarr): Browser extension for adding movies to Radarr or Series' to Sonarr while browsing IMDB or TVDB.


- [Invitarr](https://github.com/Sleepingpirates/Invitarr):  Chatbot that invites discord users to plex.


- [Gaps](https://github.com/JasonHHouse/gaps):  Gaps searches through your Plex Server or local folders for all movies, then queries for known movies in the same collection.


- [Tautulli](https://github.com/Tautulli/Tautulli):  Application for monitoring, analytics and notifications for [Plex Media Server](https://plex.tv/).


- [Unpackerr](https://github.com/davidnewhall/unpackerr):  It checks for completed downloads and extracts them so Radarr and/or Sonarr and/or Lidarr may import them.


- [mdblist.com](https://mdblist.com/): listrr.pro alternative with scrapped movie ratings from imdb, tmdb, trakt, letterboxd, rottentomatoes and metacritics. 

&nbsp;

## **► How do I torrent?**

---

&nbsp;

First, you need to find a torrent file or magnet link for the content you want to download. You'll find that on websites like nyaa.si. These sites are also called [trackers]().

A .torrent file can be added to the client by simply opening by double clicking or browsing to the location and opening it from within the client.

A magnet link can be opened by pasting into the client or by clicking on it within the browser. It'll prompt for allowing your torrent client to open, check always allow on that for an easier experience.

Most clients will begin leeching/downloading when you add the torrent, and being seeding/uploading once just a few pieces have downloaded, then will continue seeding after the torrent finishes downloading.

&nbsp;

## **► Advanced**

---

&nbsp;

### **qBitTorrent features**

They're all available in most clients, but we're using qBit as an example. The functionality is broadly divided into 3 tabs visible in the top bar - Transfers, Search and RSS. If they aren't visible, you can enable them from the View menu.

**Transfers** - This is where you can see all the torrents, which can be filtered by status, category and tags in the left pane. Categories and tags can be updated by selecting the torrents > right click.

**Search** - This is one of the most powerful features of qBittorrent. You need to enable search plugins by clicking the button at bottom left > check for updates. That will populate the list with some of the common trackers. Unfortunately, nyaa is not one of the default plugins, but it's available at http://plugins.qbittorrent.org with instructions on how to install them.

A better method is to add multiple trackers through the default search plugin called Jackett. Jackett is a separate program which has to be installed and can be configured with most private and public trackers, this plugin allows qBittorrent to search through Jackett.

&nbsp;

### **RSS**

This is the simplest way of automating downloads. It's a link on a website that is autogenerated by that website whenever a new torrent is listed on it. It takes the metadata of that torrent and lists it on its site, but it also puts the information into an file called an RSS feed.

Most torrent clients can automatically check this file every once in a while and automatically download the torrents within, and can be filtered based on various things like name, uploader, size, format, quality, or encoding, as long as it's listed in the information on the feed.

**Note:** The client can be left running in the background, and it'll download the episode as soon as it comes out.

&nbsp;

### **Swarm connections**

The concepts of connectability and port forwarding are all about the first step of connecting to peers, once you're connected, no matter how, you'll get the same speeds. However, a properly configured setup increases the pool of potential peers to connect to. This won't make a difference with torrents that have hundreds of seeds, but can drastically increase speeds on torrents with less seeds. A torrent client will still work with closed ports.

**If your port is closed, you can only connect to those who have their port open.** If it's open, you can connect to everyone.

The tracker is a server that gives you a list of peers to connect to. A few trackers are enough, please don't paste in huge tracker lists copied from random places, they don't help. Often, trackers aren't even needed when you have DHT/PEX enabled, though they do help with starting the process of finding more peers through PEX. If it's'a public torrent then all seeds/peers will find each other eventually using DHT/PEX regardless of any trackers.

&nbsp;

### **Port forwarding**

Port forwarding is useful to make sure you are fully connectable to maximize your speeds and ability to connect to other peers in a swarm.

Your connection is assigned a public IP address by your ISP and your device is assigned a private/local IP address by your router. On your computer, services which need to connect with other devices over any network run on a port. The IP address plus port number is its identification, this combination can be used to access the service in the format IP:port.When you run the torrent client, it runs on a port on your computer's IP address, which is local and can only be accessed by devices connected to your home network. 

This port on your internal IP has to be forwarded/connected to the equivalent port on your external/public IP. Once that is done, anyone over the internet will be able to connect to your torrent client through that port on your public IP as the connection will be forwarded by your router to where the torrent client is running on your internal network. Note that this is completely safe.

The port used by your client can be found in Settings > Connection. It is usually a number above 10000 or so. (preferably [49152 or higher](https://en.wikipedia.org/wiki/Ephemeral_port), some ISPs rate limit lower port numbers). **This port number should not be port 80 or 6881-6889.**

Use http://www.canyouseeme.org to check if the port of your torrent client is forwarded. Use http://portforward.com for instructions on how to port forward for your router. If setting up a port forward in your network router do not use port triggering. Optionally, in your ISP router/modem, disable all things resembling flood protection, DDoS protection, traffic shaping, QOS etc.

&nbsp;

### **What is a seedbox?**

A seedbox is a server, a computer in a datacenter with high bandwidth/speeds. It's commonly used as a service that leeches torrents for you and provides the files in a direct download format, or uploads them to a cloud drive of your choice. They also seed the torrents, and have high upload speed, and so they're used by Private Tracker users. Since the seedbox has a high upload speed compared to regular peers in the swarm, it is more likely to be chosen to upload pieces. Typical advantages:

  - Faster download speeds to the seedbox, which can then be directly transferred to you.
    

  - Seeding: A seedbox is on 24/7 seeding your torrents at high speeds, that allows you to maintain a good ratio on private (and public) trackers.
    

  - Running your own VPN (If you're paying for a VPS, you can set up whatever you like on it- not just a VPN. However, if you're only paying for a seedbox that will not be possible.
    

  - Many seedboxes support third-party plugins such as Sonarr, Plex servers, etc.

Check out r/seedboxes for more information. They are geared towards private trackers so be sure to check for public tracker support and unlimited bandwidth with any seedbox provider.

&nbsp;

## **► Trackers**

---

&nbsp;

### **Public**

- Nyaa.si (mirror - meowinjapanese.cf)


- Nyaa.net (another Nyaa, different than the others)

  
- AnimeTosho

  
- Anidex

  
- Rutracker (Russian, Google Translate works fine)

&nbsp;

### **Private**

- AnimeBytes
  

- BakaBT 
  

- AnimeTorrents
  

- U2
  

- Skyeysnow (open signup)

Lists of best releases:

- [SeaSmoke's Anime Index](https://docs.google.com/spreadsheets/d/1emW2Zsb0gEtEHiub_YHpazvBd4lL4saxCwyPhbtxXYM/htmlview#)


- [A Certain Fansubber's Index](https://docs.google.com/spreadsheets/d/1PJYwhjzLNPXV2X1np-S4rdZE4fb7pxp-QbHY1O0jH6Q/htmlview)

&nbsp;

### **How do I join private trackers?**

Typically by open signups, interviews, applications, recruitment and user invites. The ways to get into common private anime trackers are given below:


- AnimeTorrents (AnT/AnimeZ): Usually has open signups once or twice per year, typically towards the end of the year around the holiday season. /r/opensignups is a good resource to figure out when they're open. AnT also allows users to buy invites for their friends with bonus points but the page for sending invites has been broken for years and won't be fixed anytime soon.


- BakaBT (BBT): only allows new registrations from users who successfully pass an interview via IRC. The interview is mostly about the rules and information that you can find on their wiki.


- U2: used to recruit on select Chinese trackers in the past and also has user invites. You should not consider user invites to be a valid path to U2.


- AnimeBytes (AB): recruits from select few top tier trackers and also has user invites. Please note that:

    - RED is the only entry level tracker that AB recruits on and it is *extremely* difficult to survive on RED. The AB recruitment thread on RED requires you to be at least at power user (min 2 week old account, uploaded at least 5 torrents, 25GB uploaded, and >0.65 ratio) **and** your account must be at least 12 months old. If you were able to pass the RED IRC interview today, you would still have to wait over a year to join AB.
    
    - Users are responsible for who they invite on AB. The actions of the invitee can result in a ban for the inviter, as well as the entire invite tree, which results in people being unwilling to share invites. You should not consider user invites to be a valid path to AB.

&nbsp;

## **► Glossary**

---

&nbsp;

- Checksum/hash:
    - A fixed-length value that is calculated based on all the data in the complete torrent that is intended to be unique to the specific torrent. Think of it like the torrent's unique ID. Used to identify the torrent to trackers and DHT.


- DHT:
    - Distributed hash table, the basis of trackerless torrents. Basically it's a giant table that, as the name implies, is distributed among all torrent clients. This table basically functions like a giant distributed tracker of all torrents that use DHT.
    

- Leech:
    1. A peer who is still downloading
    2. A user who downloads more than they upload (slang).


- Leeching:
    - Downloading from other peers in the swarm.


- Magnet link:
    - a link containing at minimum the checksum of the torrent. May also contain the torrent name and/or one or more trackers. Since the magnet link doesn't contain torrent metadata, the .torrent file must be downloaded from the swarm first before the actual torrent can begin. Without any trackers, a magnet link requires DHT to find initial peers and begin downloading the .torrent file.
    

- Peer:
  - Any person who is uploading/downloading a torrent.


- Ratio:
    - The number of bytes of data you've seeded to others divided by the number of bytes of data you've downloaded from others. If you download a 2GB movie, and you've seeded 1.5GB, your ratio on that torrent is 0.75 (1.5/2.0).

    
- Seed:
  - A peer who has finished downloading the torrent and is now uploading it to other peers.

    
- Seeding:
  - Uploading to other peers in the swarm.


- Swarm:
    - The entire network of peers.


- Torrent file:
    - A small file with a .torrent extension that you download to begin torrenting. Contains metadata about the torrent (checksum, list of files and their sizes, etc).
    

- Tracker:
  - A server that clients talk to to get up-to-date lists of peers from the swarm. Each torrent may have zero, one, or many trackers. Private trackers are websites that run their own private tracker. All torrents from a private tracker website will use only that private tracker.


- Trackerless torrent:
  - A torrent that doesn't use any trackers. Peers share lists of peers with each other instead.

    
- PEX:
  - Peer exchange. This protocol allows peers on the same torrent to exchange lists of peers with each other. It's not as powerful as DHT because it can't be used to join a new trackerless torrent; you have to know which peers to ask before you can ask.

    
&nbsp;

## **► Related Subreddits**

---

&nbsp;

- /r/trackers - For discussion of public and private torrent trackers. No requests of specific pirated titles.


- /r/Invites - Request and offer invites for private trackers that allow for invites to be distributed through such means.


- /r/OpenSignups - Announcements of private trackers that have opened up registration or applications. opentrackers.org is another great resource


- /r/VPN - Discussion of VPNs


- /r/VPNTorrents - Discussion of VPNs for the purpose of torrenting


- /r/torrents - For torrents dicussion and news


- /r/seedboxes - For discussion, sourcing, and recommendations about seedboxes. (/r/seedbox is closed.)

&nbsp;

## **► Related Sites**

---

&nbsp;

- [encode.moe](https://encode.moe): Guides on how to encode media and various related things.

&nbsp;

---

&nbsp;

Written by /u/V_Sharp, /u/arihan77, /u/failedsatan, /u/BigBlackCough