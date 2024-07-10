# IPTV m3u Playlists for Swiss Providers

Still waiting iptv stream multicast from upc (now: sunrise upc)

This repository contains M3U playlist files for Swiss IPTV Providers. Here are the files available:

IPTV open channels from Netplus + Swisscom as language french only, english only, german only, italian only.

**https://iptv-ch.github.io/tvopenchfr.m3u**

**https://iptv-ch.github.io/tvopenchen.m3u**

**https://iptv-ch.github.io/tvopenchde.m3u**

**https://iptv-ch.github.io/tvopenchit.m3u**

## CityCable TV Lausanne ftth

**https://iptv-ch.github.io/citycable.m3u**

special thanks to bendreth for their update for community and customers of CityCable TV Lausanne over ftth date 2019-12-18

## Netplus TV HD + SD (codec video h264)

**https://iptv-ch.github.io/netplus.m3u**

Many of the channels available on [Netplus TV partners](https://citycable.ch/tv/chaines-tv/tv-numerique/).<br>
This will only work on your home network if netplus partners like Citycable (old BoisyTV) is your broadband provider.<br>
This file only lists the HD channels in the case where a channel is available on both HD and non-HD.<br>
EPG information from https://xmltv.ch/ are included.<br>
[More information](https://www.regardtv.net/t7600-netplus-iptv-gratuit-free).


## Swisscom TV SD only (codec video h264)

**https://iptv-ch.github.io/swisscom-sd.m3u**

Many of the channels available on [Swisscom TV](https://www.swisscom.ch/en/residential/internet-television-fixednetwork/swisscom-tv.html).<br>
This will only work on your home network if Swisscom is your broadband provider.<br>
This file only lists the SD channels.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information](https://www.regardtv.net/t6105-flux-iptv-swisscom).


## Swisscom TV HD + SD (codec video h264)

**https://iptv-ch.github.io/swisscom-hd.m3u**

Many of the channels available on [Swisscom TV](https://www.swisscom.ch/en/residential/internet-television-fixednetwork/swisscom-tv.html).<br>
This will only work on your home network if Swisscom is your broadband provider.<br>
This file only lists the HD channels in the case where a channel is available on both HD and non-HD.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information](https://www.regardtv.net/t6105-flux-iptv-swisscom).

## Swisscom TV UHD only (required codec video h265)

**https://iptv-ch.github.io/swisscom-uhd.m3u**

Many of the channels available on [Swisscom TV](https://www.swisscom.ch/en/residential/internet-television-fixednetwork/swisscom-tv.html).<br>
This will only work on your home network if Swisscom is your broadband provider.<br>
This file only lists the UHD channels.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information]( https://www.regardtv.net/t6105p325-flux-iptv-swisscom#77698 ).

**https://iptv-ch.github.io/SwisscomIPTV-brut.m3u**

Only channels available on [Swisscom blue TV](https://www.swisscom.ch/en/residential/tv/channel-lists.html).<br>
This will only work on your home network if Swisscom is your broadband provider or partner sharing or hosted on Swiscom network ISO layer3<br>
--== Warning: This file list SD/HD/UHD channels by ip order stream open and scrambled ==--<br>
No TV Guide/Electronic Program Guide, EPG managed by your media center <br>

## Sunrise TV SD/HD (codec video h264) (legacy network trough netstream network ended)

iptv-ch.github.io/sunrise-tv.m3u end of life

Many of the channels available on [Sunrise TV](https://sunrise.ch/tv).<br>
This will only work on your home network if Sunrise/netstream is your broadband provider.<br>
This file lists the Sunrise TV SD/HD channels.<br>
EPG information from https://xmltv.ch/ is included.<br>
[More information](https://www.regardtv.net/t6207-sunrise-iptv-libre-en-clair-non-brouille).

## Sunrise Radio 
(mpeg1-layer2 mpg-audio, datarate=256kbit/s sampling=48khz 32bit)

iptv-ch.github.io/sunrise-radio.m3u (legacy network trough netstream network ended)

Many of the channels available on [Sunrise TV](https://sunrise.ch/tv).<br>
This will only work on your home network if Sunrise/netstream/Swisscom is your broadband provider<br>
This file lists only radio channels.<br>
[More information](https://www.regardtv.net/t6207-sunrise-iptv-libre-en-clair-non-brouille)

## Init7 TV7

### Channel Overview:
https://www.init7.net/de/tv/channels/ 

### Playlists
* **Multicast**: [XSPF (VLC)](https://api.init7.net/tvchannels.xspf) / [M3U](https://api.init7.net/tvchannels.m3u)
* **HLS**: [XSPF (VLC)](https://api.init7.net/tvchannels.xspf?rp=true) / [M3U](https://api.init7.net/tvchannels.m3u?rp=true)

#### SRG Sender Full HD?
> Die SRG stellt Ihr FHD Signal nur im H.265 Format zur Verfügung. Dieses Format erfordert sehr viel mehr Hardware Ressourcen, so dass dies nur mit den aktuellsten Apple TV und >Android TV Setup Boxen ruckelfrei funktioniert. Wir verzichten generell auf Transcoding sondern fokussieren mit unserem TV7 auf die unverschlüsselte Weiterleitung von TV-Signalen. Darum verbreiten wir diese Sender in der TV7 App nicht in FHD sondern nur im 720p Format. Dafür stellen wir die Signale in FHD als separate Playlist zum Konsum auf einem eigenen Player zur Verfügung:

**Playlist Multicast**
* [SRG Sender FHD MC.m3u](https://www.init7.net/de/support/faq/srg-sender-full-hd/srg-fhd-mc.m3u)
* [SRG Sender FHD MC.xspf](https://www.init7.net/de/support/faq/srg-sender-full-hd/srg-fhd-mc.xspf)

Apple TV (tvOS) Apple TV 4 and 5 and above, olders are not supported.
https://www.init7.net/en/support/faq/tv-apple-geraete/

Android TV Android 7.0 onwards.
https://www.init7.net/en/support/faq/tv-android-geraete/


All channels available (191) if Init7 is your broadband provider<br>
This file lists SD (80) and HD (111) channels. replay (158) <br>
[More information](https://www.init7.net/en/tv/offer/
