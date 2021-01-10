# **Auto-Downloading New Episodes via Torrent**

---

&nbsp;

This guide uses qBittorrent and the SubsPlease RSS feed, but the process is similar for other clients.

**Preparations:**

1. Enable `RSS Reader` from `View` on the toolbar. It'll appear as an `RSS` tab next to `Transfers` and `Search`
   

2. Next, in that same toolbar go to `Options(gear icon)` > `RSS` tab.

   
3. Tick `Enable fetching RSS feeds` and  `Enable auto downloading of RSS torrents.`

https://i.imgur.com/vmAjcpA.png

5. Press `OK` to save your settings

6. Choose the quality you want to download and copy the corresponding link:


- 720p: [https://subsplease.org/rss/?t&r=720](https://subsplease.org/rss/?t&r=720)


- 1080p: [https://subsplease.org/rss/?t&r=1080](https://subsplease.org/rss/?t&r=1080)


- All resolutions: [https://subsplease.org/rss?t](https://subsplease.org/rss?t)

Do **not** paste this in a browser, since it will do nothing.

7. Switch from the `Transfers` tab to the `RSS` tab in qBittorrent. This is located right below the toolbar.

8. Press `New subscription` and paste the link you copied earlier. Press `OK`. 

To set up the seasonal anime that you want to download, follow the steps below:

1. At the top-right of the RSS tab, press on the `RSS Downloader...` button.


2. In `Download Rules`, press the file icon (next to the trash can icon). A new textbox should appear. Name your filter whatever you want to.


3. Once you've created the rule, change the textbox `Must Contain:` to the title of the anime you need to auto-download. For example, `Kimetsu no Yaiba`. Use the Japanese title of the show, as SubsPlease only offers the anime in their original title.

4. In the textbox `Must Not Contain:`, write `batch` to avoid downloading the batch when the season ends.


5. If your filter works, you'll see an entry under `Matching RSS Articles`


6. Check `Save to a Different Directory` and then choose where you want the downloaded episodes to save.


7. Finally, check `SubsPlease RSS` under `Apply Rule to Feeds`.


8. Repeat for every seasonal anime you want downloaded.


**NOTE:** The client can be left running in the background, and your favorite seasonal anime will now auto download whenever a new episode is out.

**NOTE:** When you first add an anime to the list, the previous episodes may start downloading automatically. This only happens once, but you can always stop the download process from happening for each unwanted episode.

Erai-raws is an alternative, exclude "v0" releases with the "Must not contain:" filter unless you want double downloads. 

You can use nyaa to get an RSS feed of all the release groups, including SubsPlease, combined. You can also make a search or navigate to a user and click RSS to get a custom feed.

Also check out this https://iamscum.wordpress.com/guides/taiga/ guide for a better way of automating downloads and tracking synced with your anilist account.

---

&nbsp;