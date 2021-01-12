# **Auto-Downloading New Episodes via Torrent**

---

&nbsp;

This guide will use qBittorrent and the SubsPlease RSS feed as an example. If you chose to use another feed, the process should be exactly the same. For other clients, please refer to its documentations to know where the features are located.

**Preparations:**

1. On the toolbar:
   - Go to `View` and enable `RSS Reader`. A new `RSS` tab will appear next to `Transfers`.
   - Go to `Tools` -> `Options`, select the `RSS` tab:
      1. Check `Enable fetching RSS feeds` and set `Feeds refresh interval` to 15 minutes.
      2. Check `Enable auto downloading of RSS torrents.` Your options should look like [this](https://i.imgur.com/vmAjcpA.png).
      3. Press `OK`.
    

2. Choose the quality that you want to download and copy the corresponding link:
      - 480p (SD): [https://subsplease.org/rss/?t&r=sd](https://subsplease.org/rss/?t&r=sd)
      - 720p: [https://subsplease.org/rss/?t&r=720](https://subsplease.org/rss/?t&r=720)
      - 1080p: [https://subsplease.org/rss/?t&r=1080](https://subsplease.org/rss/?t&r=1080)
      - All resolutions: [https://subsplease.org/rss?t](https://subsplease.org/rss?t)

    **Note:** Do **not** paste this in a browser because it will do nothing.


3. Go to the `RSS` tab:
    1. Choose `New subscription` and paste the link you copied earlier.
    2. Press `OK`.

To set up the seasonal anime that you want to download, follow the steps below:

1. At the top-right of the RSS tab, press on the `RSS Downloader...` button.


2. In `Download Rules`, press the file icon (next to the trash can icon). Pick a name for your filter (anything works).


3. Change the textbox `Must Contain:` to the exact title of the anime you need to auto-download. Use the Japanese title of the show, as SubsPlease only offers the anime in their original title. For example, `Kimetsu no Yaiba`.


4. **Optional:** In the textbox `Must Not Contain:`, write `batch` to avoid downloading the batch when the season ends. 
   

5. If your filter works, you'll see the entries under `Matching RSS Articles`.
   

6. **Optional:** Check `Save to a Different Directory` and choose the download directory for the episodes.


7. Check `SubsPlease RSS` under `Apply Rule to Feeds`.


8. Repeat the steps for every seasonal anime you want to download.


**NOTE:** The client can be left running in the background. The anime episode will be automatically downloaded whenever is released.

**NOTE:** When you first add an anime to the list, the previous episodes may start downloading automatically. This only happens once, but you can always stop the download process from happening for each unwanted episode.

Erai-raws is an alternative for SubsPlease. Exclude "v0" releases with the "Must not contain:" filter unless you want double downloads.

You can also use nyaa.si to get an RSS feed of all the release groups by searching or navigating to the user and click `RSS` to get a custom feed.

Alternatively, check out [this guide](https://iamscum.wordpress.com/guides/taiga/) guide for a better way of automating downloads and tracking synced with your Anilist account.

Happy pirating!

&nbsp;
