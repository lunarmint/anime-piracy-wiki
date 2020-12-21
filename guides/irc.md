# **How to use IRC/XDCC**

---

&nbsp;

IRC (Internet Relay Chat) is a protocol that allows communication in the form of text. XDCC is a computer file sharing method which relies on IRC as a hosting service.

The main advantage to using this method is that IRC bots are usually the fastest at uploading new anime episodes, thus being able to download them much earlier. They usually upload even faster than anime websites.

This is a guide created for people who want to use the IRC protocol to directly download anime into their computers.

Whether you choose IRC or another method is entirely up to you. I'm not here to change your mind. We've written a guide to help you choose the method that works best for you.

For this guide, we're going to be using the HexChat app to connect to the #nibl channel, from which I will teach you to download any anime episode (even in large batches).

**Let us begin!**

  > 1. Download and install HexChat from [this website!](https://hexchat.github.io/) You don't need to change any of the settings in the installer.

  > 2. The first thing you'll see when you start up the app is the network list tab, and you'll need to do the following in that tab:

Tick the **"Skip network list on startup"** option, so you don't have to see this tab again after you've configured it the first time.

  > - **User Information:** For this table, make your **Nick name** and **User name** whatever your online username is. **Second choice** should be your username, but slightly altered, in case someone has already taken whatever your nick name is. **Third choice** will be a final username, in case any of the previous usernames were already taken.

  > - **Networks:** From this list, find and select the "Rizon" network. Next, press **Edit** to the right of the network list. Switch to the **Autojoin channels** tab within that editor, then press **Add**. Type **#nibl** into the text box that appears, and press **ENTER**. If you don't press **ENTER**, the channel will not save. From the checklist below the channel tab, make sure the 2nd, 5th, and 6th option are ticked. (**Connect to this network automatically**, **Accept invalid SSL certificates,** and **Use global user information** respectively.) Finally, make sure the **character set** (located at the bottom of the editor) is set to **"UTF-8 (Unicode)"**

Press **Close** to exit this editor, then press **Connect** to finally join the network!

**Note:** You will never have to do all of the above steps again, unless you uninstall HexChat for some reason.

To continue downloading anime episodes, follow these steps:

  > 1. Go to this link: [NIBL](https://nibl.co.uk/bots.php). This is where you're gonna find all of your anime, so make sure to bookmark it or make note of the link somewhere.

  > 2. In the "Search" text box, type the name of the anime you want to download, and the quality. (Usually 480p, 720p, and 1080p). **Example:** "Dr. Stone 720p"

  > 3. Press the episode you want to download. If you want to batch download episodes, please refer to the **Batch downloading** section.

  > 4. A textbox should appear with the title "**Paste this into your IRC client"**, which is what we'll be doing. Copy the command that pops up. Follows this structure: "/msg BotName xdcc send #1234"

  > 5. Go to HexChat, and paste the command into the input box at the bottom. Then, press Enter.

  > 6. Navigate to your anime folder, if you have one, using the browser provided, then press **Save.**

Your Japanese cartoon should now be downloading! Cheers!

**Batch downloading episodes:**

To batch download a bunch of episodes from an anime, you just need to change the command a bit.

  > 1. Let's say I want to download the entire first season of My Hero Academia, so I search for "my hero academia 1080p" in the search box.

  > 2. The first results that show up are for season 3, so I scroll down to look for season 1 and I find that the bot "mdcx|akane" offers this anime.

  > 3. Press the first episode and copy the command. In my case: **"/msg mdcx|akane xdcc send #15907"**

  > 4. You want to change **"send"** into **"batch"**, and remove the **"#"** before the number. So now the command becomes: **"/msg mdcx|akane xdcc batch 15907"**

  > 5. Next, add a hyphen after the number, then look at the pack number of the last episode of that season. Finally add that pack number to the end of the command. Final command should look like this: "**/msg mdcx|akane xdcc batch 15907-15919"**

  > 6. Enter the command in HexChat and press Enter! The anime should be downloading!

**Note:** If you mess up the pack numbers, an entirely different anime could download or the one you wanted could download followed by some other random episodes.

**Note #2:** Batch downloading doesn't usually work with seasonal anime, as the pack numbers are not correctly ordered, thus a bunch of random anime will download in between the ones you wanted.

**Final settings:**

If you don't want to choose the anime folder every time a new episode wants to download, then do the following:

  > 1. Press **Settings** then go to **Preferences.**

  > 2. Next, switch to the **File Transfers** tab from the list located to the left.

  > 3. In this tab, you can select a default anime folder in the **"Download files to:"** option.

  > 4. Also, in "**Auto accept file offers:**", above the previous option, select **"Ask for confirmation"**. This way, HexChat will ask you to accept file transfers (in our case, episodes) without asking for the download folder each time. And if you get offered the wrong episode, or something malicious, you can simply reject the file from ever downloading. This ensures safety.

Again, this guide is meant for those who have already decided to use IRC themselves. If this is the method you prefer, then just follow these steps! It doesn't take that long, and once you get used to it you'll have a bunch of anime downloaded in no time!

Have fun!

&nbsp;

---

Written by /u/Altin1337 - [Original Post](https://www.reddit.com/r/animepiracy/comments/ctinwu/guide_using_ircxdcc_to_download_anime/)

&nbsp;
