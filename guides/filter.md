# **How To Bypass Web Filter**

---

&nbsp;

**Note:** This guide only applies to countries that block sites at a DNS (Domain Name Service) level, like Australia.

Things you will need:

- A Computer
- Mozilla Firefox
- Internet Connection

---

&nbsp;

Goal: We will be using Firefox's new feature, DNS over HTTPS which essentially is a DNS change. What is Domain Name Service? Basically it's like in the old movies where you call someone and a stranger redirects your call.

Now imagine that the filter is like those ladies in the photo and it denies your (internet) connection to some sites. Changing your DNS is like basically changing the ladies in the photo to ones that will connect you regardless of what you request.

---

&nbsp;

After Downloading and Installing [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/), press the [hamburger icon](https://upload.wikimedia.org/wikipedia/commons/b/b2/Hamburger_icon.svg) on the top right of the Firefox window.

It should open a list. Go down and find "Options". It should have a little cog on the left of it **OR** paste this `about:preferences` into your search bar. Either way it will take you to the same place.

Once in preferences, you should see a `Find in Options` search bar. Click on it and search for `Network Settings`. Click the `Settings` button.

Once a little window opens, scroll all the way down and at the very bottom you should enable `Enable DNS over HTTPS`. There will be a `Use Provider` dropdown box underneath with `Cloudflare (Default)`. You should leave it as is, although you can opt to use NextDNS, or choose `Custom` and use one of the following encrypted-DNS servers [here](https://github.com/curl/curl/wiki/DNS-over-HTTPS) if somehow neither `Cloudflare (Default)` or `NextDNS` works for you. However, please do research and use at your own risk.

Press `OK` and restart your browser. You should now be able to browse all the filtered sites normally.

And that's it! If you get stuck, please let me know. I will do my best to help you. If you want to do the same thing to your mobile device, you can easily do it via this free app you can get [here](https://1.1.1.1/)!

---

&nbsp;

Written by u/RubyNero - [Original Post](https://www.reddit.com/r/animepiracy/comments/d4tmfh/guide_the_easiest_way_to_stream_anime_and_bypass/)

12/21/2020: Revised by u/BigBlackCough

&nbsp;
