NZ XMLTV
=====
NZ XMLTV is the only New Zealand XMLTV that is specifically optimised for Plex, avaliable for both Freeview and SKY. With the removal of New Zealand from the default Plex guide, then this is one of the few alternative sources of data for New Zealanders.

## Features:
* Adding posters to TV shows and movies. These are both sourced from international providers (such as IMDB, TheMovieDB and TheTVDB), but also New Zealand specific providers (TVNZ, ThreeNow, SKY Go, Choice TV OnDemand and HGTV OnDemand). In cases where there is no poster avaliable, channel branded posters are generated ([example](https://imgur.com/a/ULqc7X3)).
* Added season and episode numbers to TV shows and years to movies.
* Clean up the titles to improve Plex matching (e.g. removal of the `All New: ` prefixes that are often used)
* Correctly differentiates TV shows and movies.
* A bunch of smaller tweaks that I've probably forgotten.

Each guide has goes ahead one week and automatically updates when new channels are added. In the case of Freeview, Prime PLUS 1 has also been added, even though it is not a Freeview certified channel.

## Links
Freeview - https://nzxmltv.github.io/xmltv/guide-v2.xml

SKY - https://nzxmltv.github.io/sky/guide.xml

If you only have Freeview channels, then the Freeview guide is strongly recommended over the 
SKY one, as Freeview provides significantly more (and higher quality) data, meaning both the metadata and matches are better.

## Adding it to Plex
This setup assumes you have no setup Live TV / DVR yet. If you need to add the XMLTV to an exisiting setup, click the Delete DVR link on the DVR settings page:
![image](https://aws1.discourse-cdn.com/plex/original/3X/b/1/b18c515198cdc417aa244fbbb7dca7266996da91.jpeg) 
Your scheduled recordings will be preserved.


![image](https://aws1.discourse-cdn.com/plex/original/3X/1/b/1bed660f6815045efbab9d3f8843f054358c7e03.png)
1. Select the device you want to setup and click Continue.

![image](https://aws1.discourse-cdn.com/plex/original/3X/2/a/2acc20e17c62697d166782cb974373598a0a52f0.png) 

2. Select a random country (as NZ is no longer available). I went with the UK since they use the same TV standard as us, but it shouldn't matter. The fact you have to pick a country is a bug that Plex is aware of (based off the forum posts I've seen).

![image](https://aws1.discourse-cdn.com/plex/original/3X/e/b/eb8555b54097299d79da3cc81e4d970a5e9c16d1.png) 

3. Click Scan Channels and then select 'DVB-T/T2 Europe (Full frequency range)'. Then click Scan Channels again. Plex will now scan for channels. This may take a while depending on your signal strength. Once it is done click continue.

![image](https://aws1.discourse-cdn.com/plex/original/3X/5/2/5204ce882dfcf0d2ab4f07f89d995f9976bdc306.png) 

4. On the next screen click the XMLTV link.

![image](https://aws1.discourse-cdn.com/plex/original/3X/6/1/616554343e8ba89677f792a6d423d7d26fbf8d9b.png) 

5. Select English as the language, and enter either the SKY or Freeview link into the 'XMLTV Guide' field. Do not use a file from your computer, despite what the suggested text says. Give it a title, this doesn't really matter, so it can be anything.

![image](https://aws1.discourse-cdn.com/plex/original/3X/f/a/fa30b2979a1867636b4d19acadd3ca6a692c4eef.png) 

6. You will now see the channel mapping screen. These should be automatically filled out. You can disable any channels you don't want at this stage.

**Tip:** If you want faster refreshes you can disable 'Enhanced Guide' in DVR settings. This does mean you don't get access to a few features (such as descriptions of TV shows), but makes the guide refresh much faster.

## Questions? Issues?
If you have any questions or issues please feel free to reply. If a TV show or movie has an incorrect match I can fix this up, so once again feel free to let me know in the Plex thread.

