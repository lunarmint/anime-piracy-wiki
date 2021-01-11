# Basics

&nbsp;

### Video

.mkv and .mp4 are containers. They can contain various video, audio, and subtitle streams within them. Even the exact same video can be placed in both containers. You can losslessly convert from one to the other with [ffmpeg](https://ffmpeg.org/download.html)

**Codec** - This is what most people mean when they confuse it with the container. The codec is the biggest factor in compatibility with your hardware and system. HEVC(h265/x265) and AVC(h264/x264) are the main ones.

**Bit depth** - 8-bit/10-bit - Most high quality anime encodes are 10-bit. Converting an 8-bit source to 10-bit might seem counterintuitive if you know a little about transcoding and data loss, [but it gives a better result at smaller sizes.](https://yukisubs.files.wordpress.com/2016/10/why_does_10bit_save_bandwidth_-_ateme.pdf)

**Frame rate** - This will usually be 23.976 FPS. Many TVs use [interpolation](https://en.wikipedia.org/wiki/Motion_interpolation) to turn this into 60 fps giving you an artificial sense of smoothness. This is not recommended for anime and should be turned off in your settings. 60 FPS encodes are even worse and should be avoided.

**Level/Profile** - These are specifications within the h264/h265 standard which give an idea of compatibility and specify the maximum resolution and bitrate, for example h264 4.0 = 1080p 30fps 20 Mbps. Higher level/profile = lower compatibility = more processing power needed to decode.

The full information for a video will look like - x264 High 10 .mkv (codec)(profile)(bit depth)(container)

&nbsp;

### Audio

Codecs - Audio codecs are divided into lossless(FLAC, TrueHD, DTS-HDMA) and lossy(aac, opus, mp3). While lossless raw video will be multiple GBs per minute, audio is more manageable in size, and you'll see many options with lossless audio. 

Lossless audio is unnecessary for most sound systems. Even with the best audiophile grade setup, it's nearly impossible to make out the difference. However, some exceptional music samples exist, which can be used to differentiate lower-bitrate lossy audio by repeatedly listening to small extracted samples. I'm very confident that you won't hear the difference. 

If you want to make sure, try out these [online ABX tests](http://abx.digitalfeed.net) or [Foobar plugin](https://www.foobar2000.org/components/view/foo_abx) with [this guide for setting it up.](https://www.head-fi.org/threads/setting-up-an-abx-test-simple-guide-to-ripping-tagging-transcoding.655879/#post-9268096.) This foobar plugin lets you ABX any two tracks of your choice and produces a verifiable log. If you do manage to complete it with a decent probability, hop over to our [discord]() for some interesting conversation.

A good benchmark for bitrates(stereo/2.0) is - 

128 kbps for opus

160 kbps for aac

192 kbps for mp3

Below these, the loss might be enough to adversely affect the experience. For surround audio, multiply these with the number of stereo pairs.

&nbsp;

### Subtitles

Most anime subtitles are in the .ass format, it has better styling options compared to srt. This styling often breaks when there is incompatibility somewhere in the playback process.

Fansubs use a variety of fonts in subtitles. These are bundled within the .mkv files as attachments or provided separately in a folder. They can be installed on windows or placed in your player's fonts folder for a quick solution. It's recommended to mux them in for perfect compatibility.

&nbsp;

# Sourcing

&nbsp;

## Quality

Quality might be somewhat subjective. The best release for the purpose of this guide is an encode which fixes flaws of the raw bdmv while simultaneously not altering the original material too much. There is a difference between obvious flaws which need to be fixed and your subjective preference of how you like the encode. If something apparently looks "better" because it unnecessarily alters the video, then it's not a good indication of quality. These statements might seem too complicated or a bit vague, I'll try to explain in brief, but this is beyond the scope of a guide for beginners and more into the realm of encoding.

The official BDMV, from the blurays, is itself an encode of the actual source. It often suffers from issues like banding, blocking, noise, ringing, aliasing, etc. These might be originating from a variety of reasons. For example, a lot of anime is native 720p and is upscaled to 1080p for the bluray. Even if issues aren't present in the bdmv, they can appear in the encode because of compression. This fixing is called filtering, a step which comes before encoding. The video is filtered with Avisynth/Vapoursynth before passing it on to the encoder.

- [Examples of problems](http://bakashots.me/guide/index.php)

- [Encoding guides and more examples](https://silentaperture.gitlab.io/mdbook-guide/introduction.html)

- [Mini encodes and audio](https://kokomins.wordpress.com/2019/10/10/anime-encoding-guide-for-x265-and-why-to-never-use-flac/)

&nbsp;

## Types of releases

**BDMV** - A simple complete copy of the bluray. It's used as a source for making another release or encoding, this is not useful for watching.

These can be found on U2(Chinese-Private), Skyeysnow(Chinese-Open) and nyaa(usually without seeds). Release groups don't matter for bdmvs because they're all the same unless the files are corrupted. JPBDs often have better quality than USBD because of more bitrate devoted to the video instead of multiple(dub) audio tracks. In some cases, blurays from Italy or other countries might have the best quality.

**BDRemux** - The BDMV is losslessly packaged into mkv files for ease. The sizes are huge, just like bdmvs.

**BDRip** - An encode made directly from the BDMV/BDRemux. This is the only kind of encode considered good quality.

Most can be found on nyaa with some rare stuff on rutracker(Russian). The direct encode is usually a raw(without subtitles) and is used by remuxers or fansubbers to make a release in the Anime-English Translated category on nyaa. The groups can be roughly rated as - 

- Excellent - Beatrice-Raws, Kawaiika-Raws

- Good - VCB-Studio

- Okay/Bad - Snow-raws, ANK-raws, Reinforce, Moozzi2

Remux groups will mention the sources used for video and subtitles in the torrent description. Sometimes they use their own encodes. Some good ones are - **Kametsu, CTR, SCY** and others I forgot to mention.

**WEB** - Until the blurays are released, this is the only source available for new airing anime. Note that this is not a WEBRip, as in a screen capture. The ones released by reliable groups are always direct WEB-DLs from sources like Crunchyroll or Funimation. The quality will be the same no matter which group releases these, however they often go down and reliability is a factor when you want airing anime in the shortest time possible. The most reliable one right now is SubsPlease.

**Re-encode** - Marked red on nyaa, these are usually encodes of a BDRip, WEB source or even worse. Encoding is a lossy proceess and information is lost at every stage. The same encode made from the BDMV instead of a BDRip would've been better quality. Re-encoding is considered a bad practice.

**Mini encode** - Can be either a BDRip or a re-encode, when the video stream is around 500 mb or lower. Despite a bad reputation, the minis which are not re-encodes can be a decent option for those low on storage or bandwidth. Mini groups - 

- Decent - Judas, Akihitosubs

- Bad - Nep_Blanc, DB, Cleo, Reaktor, Cerberus. The last two re-encode, and their video is most certainly bad. But they often pick good subtitles sources.

- Trash - DKB, HR, SSA, FFA and any of the other new groups re-encoding seasonal web releases.

&nbsp;

## Torrents

If you're in a rush to get something, try searching on nyaa with the recommended release from - 

- [Smoke's Anime Index](https://docs.google.com/spreadsheets/d/1emW2Zsb0gEtEHiub_YHpazvBd4lL4saxCwyPhbtxXYM/htmlview)

- [A Certain Fansubber's Index](https://docs.google.com/spreadsheets/d/1PJYwhjzLNPXV2X1np-S4rdZE4fb7pxp-QbHY1O0jH6Q/htmlview)

A lot of releases were compared by various people and compiled into these sheets to make it easier for you. However, these don't cover all the anime that exists. The subtitle preferences in that might not match with your own or the best video might not be compatible with your setup. It's always better to have an idea about these things yourself so you can always find what you need. Read on to obtain that knowledge.

&nbsp;

### Searching

The main source for finding torrents is nyaa.si, you already have a general idea about the codecs, quality and release groups from the sections above. These 3 things are what we'll use to quickly find the best release for any anime. Nyaa search is simple and limited, but it's enough for finding anything, given that the uploader correctly tags the release.

First, change the All Categories option to `Anime - English Translated`. It can be set to just `Anime` to include english, raws and other languages. The two useful search operators are `-` and `|(OR)`, `AND` is already implicit in every search. For example - 

`"Attack on Titan"|"Shingeki no Kyojin"` will return results that match either

`-` is useful when you want to exclude something. When I try to search for an anime titled just [`Monster`](https://myanimelist.net/anime/19/Monster,), the results are flooded by Pocket Monsters episodes. This can be solved by changing the search to `Monster -pocket`. 

Once you have the search results, they are sorted by date(newest) by default. Sorting by seeds or completed downloads might help in finding the best release.

&nbsp;

**Example Search**

For a complete example, let's take [KonoSuba](https://myanimelist.net/anime/30831/Kono_Subarashii_Sekai_ni_Shukufuku_wo), the long title is complicated enough to make searching hard. Suppose I want to watch this on a TV, and a compatibility check reveals that I can't play x264 10-bit(hi10p) . 

For the video, hevc/x265 10-bit gives me the best size/quality. And I want the superior video from a bluray, with fansubs, instead of a web release. For some reason, I also desire flac even though it's completely irrational. So my search becomes

`Konosuba BD 1080 hevc flac`

Most releases are tagged both hevc and x265, explicitly mentioning only 265 like `Konosuba BD 265 flac` will also give you some results where the uploader forgot to tag hevc. If I don't want flac, it'll be `Konosuba BD hevc -flac` or `Konosuba BD hevc opus`. There's still a big flaw in this search, we used `konosuba` instead of the full name and some stuff is missed because of that. Changing it to `Kono BD hevc flac` matches everything. Now we can sort the results and immediately see one by kawaiika-raws. Aware of the fact that they usually have the best video and often pick good fansubs, you can safely download it.

Note that all of the above information is intentionally complicated to give you a better idea of the process. What you'll need for most actual searches is just `Anime name BD` or `Anime name hevc` for smaller sizes.

&nbsp;

### Fansubs

Older anime was subbed by a variety of fansub groups. Every good release will mention the sources used for subtitles, the edits made, and often describe their choice of subtitles. A very good resource for fansub reviews was MyAnimeList. They removed the fansub reviews section a few years ago towards their goal of legitimization, since fansubs are associated with piracy. Luckily, the data was archived and [can be brought back on the MAL page itself through this](https://www.reddit.com/r/anime/comments/9kq1ch/bringing_fansubs_back_on_mal/). Fair warning, the reviews are mostly filled with hate and trolls but often give you an idea of which group used which script. You can also make out the kind of translation and how much it is localized. Localization means changing cultural references and puns to fit the English or sometimes American context. A degree of localization is always involved with translation to make sure the dialogue flows smoothly, but some people may find too much of it a problem. 

Most newer fansubbed anime is some variation of edited official subs from CR or Funi. These edits are usually range between excessive localization by completely eradicating the idea of Japan and replacing it with America or complete untranslation by changing random phrases and lines back to Japanese for no apparant reason. Although those are exaggerations, the real fansubs lie somewhere in between. After looking at the work of a few groups, you'll soon realize who has a tendency to do what.

AnimeTosho is a very useful resource for grabbing just the subtitles from any release on nyaa. You search the title as it is on nyaa and after opening the page you'll see `All Attachments` near the bottom. This will download all subtitles and fonts extracted from that release. It's also useful to get the mediainfo when the uploader hasn't posted it, to do this, just click on any of the mkv files in the torrent and you'll get details about it. Animetosho is also a DDL site which uploads torrents from nyaa to various hosting services. There's also an NZB option, but none of these last for long.

&nbsp;

## DDL

- XDCC - Downloads over IRC, many anime groups offer this and it can be useful to obtain content with dead torrents.

- Anichiraku(private) - Stuff from nyaa and other places mirrored to google drive to provide you with fast direct downloads.

- Animetosho(usenet) - mirrors most torrents posted on TokyoTosho, Anidex and Nyaa's English translated anime category onto various file hosting services, as well as usenet. Screenshots, mediainfo, subtitles are also extracted and posted.

&nbsp;

# Playback

&nbsp;

## Compatibility

Decoding is the process of playing the video file. There are two types - hardware and software. Everything can be decoded, the difference is in the amount of work needed to do that. When it's hardware accelerated, it doesn't put any strain on your device cpu.

Most PC players will decode everything with swdecode as a fallback option. The problem is when this decoding isn't fast enough to play your video in real time. That won't ever be a problem is hwdecode is supported for that codec.

If you're watching on a TV/+Android box, you'll see a list of supported codecs in their specifications. Plex and other media servers will recognize a format as not supported and start transcoding to h264 8 bit. Kodi player is the better option it'll fallback to software decoding like on a PC, giving you the option to always direct stream or run without a server. However, since the cpu on your tv/box is much weaker compared to a PC, there will be instances of horrible lag when trying to force swdecode. Note that software decoding utilizes your cpu, so the cause of lag isn't limited to decoding. It's anything that might be using your cpu at the time. Like when there's a lot of complicated .ass typesetting which needs to be rendered, that will lag with a weak cpu no matter what the video codec is. Generally - 

h264 8-bit works everywhere
h264 10-bit rarely works without a decent cpu. Hardware decode for this is non-existent.
h265 8-bit and 10-bit work when hardware support exists. Most newer devices in the last 5 years support it.

&nbsp;

## Video players

**PC**

- [mpv](https://mpv.io/installation/) (Recommended - Highly customizable) - [Config Guide](https://iamscum.wordpress.com/guides/videoplayback-guide/)

- [Potplayer](https://potplayer.daum.net)

**TV**

For a dedicated HTPC box: 

- [Kodi](https://kodi.tv), optionally through [LibreElec(Minimal OS)](https://libreelec.tv)

For a Client-Server model: 

Kodi player on your TV and a media share(smb,nfs) from your pc is the simplest. Kodi can also be configured with media servers. Other options are - 

- [Plex](https://www.plex.tv/)

- [Emby](https://emby.media/)

- [Jellyfin](https://jellyfin.org/)

Transcoding on these media servers utilizes the cpu on your machine where it is hosted. It allows all client devices to play everything by converting the video to a supported codec.

- [Kodi's Plex Add-on](https://kodi.tv/plex-add-on-for-kodi)

- [Emby's Kodi addon](https://emby.media/emby-for-kodi.html)

&nbsp;

## Advanced

Typesetting - Anime usually has .ass subtitle styling, while the subs will show up on most TVs and players (plex, emby, jellyfin etc.), the typesetting or overlapping dialogue is sometimes broken. This is especially a problem if you're watching fansubs. **Kodi** is one of the few players which supports proper ass rendering. Note that the player is separate from the kodi media server and can even be used with plex.

Ordered Chapters/mkv linking -  On some releases(like coalgirls), the OP/ED are removed from the episodes and placed into separate files. These files are then linked to the appropriate position in the episodes where they are supposed to play. While this is a great idea to save space, unfortunately, it doesn't work on a lot of players and the OP/ED is never played. If you notice this while watching anime, OCs are the most probable cause.

&nbsp;

### Muxing

Matroska(mkv) is a very versatile container. It can contain multiple streams of video, audio, subtitles, and other attachments. The process of taking these streams, adding or removing some, and bundling them into a new mkv is called muxing. In general, you could be muxing any format, but for anime we'll mostly be dealing with mkv.

Suppose you want to use subtitles from a different release with what you already have downloaded, or to remove the extra english audio tracks to save space, that is when muxing is useful.

[Mkvtoolnix](https://mkvtoolnix.download/) is the best tool for all kinds of muxing. The equivalent cli option is mkvmerge(installed with mkvtoolnix) or ffmpeg.
