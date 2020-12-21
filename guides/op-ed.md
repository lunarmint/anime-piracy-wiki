# **How to download every OP/ED from your MAL or AniList account**

---

&nbsp;

I was looking for a way to download every opening and ending from my AniList. Themes.moe is a super useful site that lets you search for your profile and it will show each OP and ED associated with all the anime in your list. However it only lets you save them as webm files which isn't useful for me as I only want the audio to put on iTunes.

Below is the process I used to download practically every OP/ED from my profile, extract the audio from the webm files, and save them as mp3 files. Note that this was done in Windows, if you use Linux then I think you could use [this script instead](https://bytefreaks.net/gnulinux/bash/ffmpeg-extract-audio-from-webm-to-mp3).

**You will need:**

  > - A Browser - I used Firefox.

  > - A downloader that grabs all links on a page - I use the [DownThemAll!! add-on for Firefox](https://addons.mozilla.org/en-US/firefox/addon/downthemall/). I believe that they have released this add-on for Chrome as well.

  > - [ffmpeg](https://ffmpeg.zeranoe.com/builds/) - This will be used to extract the audio from the webm files.

  > - Winrar/7Zip or any other file archiver - To extract the files from the ffmpeg download

**Instructions:**

  > 1. Download ffmpeg, open it in your file archiver tool, navigate to the bin folder and drag the 3 .exe files to a new folder (I created a separate folder called "ffmpeg" in my Music folder)

  > 2. Go to [themes.moe](https://themes.moe/), select Anilist or MyAnimeList, enter your username and click the search button. When it shows all the OP/EDs for your profile, you will want to click on the "Filters" button and disable "Include Duplicates" so that you don't have the same audio twice. You can also get rid of other things like stuff on your Plan To Watch list, or to only show OPs. Just customize it so that it only shows what you want to download.

  > 3. If you have the DownloadThemAll!! extension, then click on it (in your extension bar) whilst on your themes.moe page and click "DownloadThemAll!!"

  > 4. It will bring up all the links on that page, ensure that only the "Videos" filter is selected so that it only selects the webm files and click "Download". This will now start to download all the OP/ED files on that page, it will take time to download them all if you have lots of anime on your list. You don't have to do it all in one sitting, just pause and start them up again later.

  > 5. When they are downloaded, move them to the same folder where ffmpeg is.

  > 6. Copy the code from [this pasterbin](https://pastebin.com/wH0PScSf) into notepad and save it with the `.bat` extension and in the same folder as ffmpeg and all your webm files. You can also change the bit rate if 128k is too low for you, just bear in mind that if you increase the bit rate then the size of them mp3 file will increase. If you don't want it to delete the webm file after it creates the mp3 then just remove the 3rd line.

  > 7. Run the .bat file. It will now start to extract the audio from each webm file in the folder and save them in an mp3 format.
Great! All of the OP/EDs should now be completed!


**NOTE:** The songs downloaded are TV size.

---

&nbsp;

Written by /u/ZeMuffenMan - [Original Post](https://www.reddit.com/r/animepiracy/comments/d44j33/tutorial_how_to_download_every_oped_in_your/)

&nbsp;
