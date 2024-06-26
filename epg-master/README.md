### Update 29/10/2022
No EPG updates this week. Will be updating on 5/11/2022.

# What's this all about?
This repository contains all the XMLTV data for Malaysian TV providers. All grabbed from respective providers.

## Important information
Do not fork it unless you want to change something on the configuration files, as it will not update the EPG by itself! If you want to update it, modify "GenerateAll.bat" to point to your WebGrab directory and repository directory. Make sure you have git setted up on the epg directory (you might have to use ``del .git`` to delete the existing one, then link it to your own fork). If you want to update it locally, delete all lines that contain the "git" command.

# About
This repository is for Malaysian TV Channels (and some Southeast Asian ones, too) and anyone can use it.

# What to know before using this EPG
- This EPG is free-of-charge and **NOT for sale** at any platforms! You can use these links for your YouTube tutorials, blogs, and more.
- All rights reserved to the respective companies. Special thanks to Astro, RTM and unifi TV for providing the channel guide.

# Viewing EPG on your PC
You can download the EPG data (see "What's available in the guides") and open it with any compatible XMLTV viewer. I recommend using [ERD XMLTV Viewer](https://erdesigns.eu/app/freeware/view/4).

# Viewing EPG on your IPTV client
If you have a IPTV client that supports XMLTV, see section "What to put on XMLTV ID on your playlist?".

# Credits
Thanks to Khalis (@hantu08 on Telegram) for helping me doing some WebGrab+Plus stuffs, including:
 - Access to unifi TV Channel Guide directly from playtv@unifi  
 - Access to the new Astro Guide page (content.astro.com.my)
 - Access to the new RTM Klik SiteIni

# What to put on XMLTV ID on your playlist?
If you have a playlist to use with this XMLTV EPG data, add `tvg-id="(XMLTV ID HERE)"` before the comma before the channel name. Example:
```
#EXTINF:-1 tvg-id="101",TV1
```

## Astro
The XMLTV ID is the channel number itself, for example: `101` is the Channel ID for `TV1 HD`.

## unifi TV
From now on, unifi TV EPG data will be using channel names as XMLTV ID. These channels have EPG data:
> - unifi Sports 1
> - unifi Sports 2
> - unifi Sports 3
> - unifi Sports 4
> - SPOTV
> - SPOTV2
> - SONY YAY
> - DreamWorks Kids
> - Nick Jr.
> - CBeebies
> - Nickelodeon
> - Boomerang
> - Rock Extreme
> - BBC Earth
> - Love Nature 4K
> - BBC Lifestyle
> - Luxe TV
> - Dunia Sinema
> - tvN Movies
> - Zee Thirai
> - Colors Cineplex
> - CinemaWorld
> - BBC World News
> - Al Jazeera HD
> - CGTN
> - CNA
> - EuroNews
> - WION
> - Parlimen Malaysia
> - ABC Australia
> - DW English
> - NHK World Japan
> - France 24
> - tvN
> - Paramount Network
> - WBTV
> - Rock Entertainment
> - MTV Live
> - Colors HD Tamil
> - 8TV
> - Now Jelli
> - CCTV4
> - SET International
> - TV1
> - TV2
> - TV3
> - Didik TV
> - TV9
> - Salam HD
> - TV Alhijrah
> - Sensasi
> - Inspirasi
> - Degup
> - Dunia Sinema
> - Pesona
> - Laku Mall

## RTM Klik
From now on, RTM Klik EPG data will be using channel names as XMLTV ID. These channels have EPG data:
> - TV1
> - TV2
> - Okey
> - Sukan RTM
> - Bertia RTM
> - TV6
> - Dewan Rakyat
> - Dewan Negara
> - Radio Klask
> - Nasional FM
> - Traxx FM
> - AI FM
> - Minnal FM
> - Asyik FM
> - Selangor FM
> - SabahV FM
> - Sarawak FM
> - Labuan FM
> - Kedah FM
> - KL FM
> - Kelantan FM
> - Terengganu FM
> - Pahang FM
> - Johor FM
> - Negeri FM
> - Negeri FM
> - Perak FM
> - Mutiara FM
> - Perlis FM
> - Melaka FM
> - Sabah FM
> - Wai FM
> - Red FM
> - Langkawi FM
> - Limbang FM
> - Miri FM
> - Sri Aman FM
> - Bintulu FM
> - Sibu FM
> - Sandakan FM
> - Tawau FM
> - Keningau FM

## MYTV Broadcasting
The XMLTV ID is the channel number itself, for example: `101` is the Channel ID for `TV1`.

# Extras
No information available for any of your channels? Change the XMLTV ID to CHN to display a "Channel Information Not Available" notice on your EPG guide.
### Update 29/10/2022
No EPG updates this week. Will be updating on 5/11/2022.

# What's this all about?
This repository contains all the XMLTV data for Malaysian TV providers. All grabbed from respective providers.

## Important information
Do not fork it unless you want to change something on the configuration files, as it will not update the EPG by itself! If you want to update it, modify "GenerateAll.bat" to point to your WebGrab directory and repository directory. Make sure you have git setted up on the epg directory (you might have to use ``del .git`` to delete the existing one, then link it to your own fork). If you want to update it locally, delete all lines that contain the "git" command.

# About
This repository is for Malaysian TV Channels (and some Southeast Asian ones, too) and anyone can use it.

# What to know before using this EPG
- This EPG is free-of-charge and **NOT for sale** at any platforms! You can use these links for your YouTube tutorials, blogs, and more.
- All rights reserved to the respective companies. Special thanks to Astro, RTM and unifi TV for providing the channel guide.

# Viewing EPG on your PC
You can download the EPG data (see "What's available in the guides") and open it with any compatible XMLTV viewer. I recommend using [ERD XMLTV Viewer](https://erdesigns.eu/app/freeware/view/4).

# Viewing EPG on your IPTV client
If you have a IPTV client that supports XMLTV, see section "What to put on XMLTV ID on your playlist?".

# Credits
Thanks to Khalis (@hantu08 on Telegram) for helping me doing some WebGrab+Plus stuffs, including:
 - Access to unifi TV Channel Guide directly from playtv@unifi  
 - Access to the new Astro Guide page (content.astro.com.my)
 - Access to the new RTM Klik SiteIni

# What to put on XMLTV ID on your playlist?
If you have a playlist to use with this XMLTV EPG data, add `tvg-id="(XMLTV ID HERE)"` before the comma before the channel name. Example:
```
#EXTINF:-1 tvg-id="101",TV1
```

## Astro
The XMLTV ID is the channel number itself, for example: `101` is the Channel ID for `TV1 HD`.

## unifi TV
From now on, unifi TV EPG data will be using channel names as XMLTV ID. These channels have EPG data:
> - unifi Sports 1
> - unifi Sports 2
> - unifi Sports 3
> - unifi Sports 4
> - SPOTV
> - SPOTV2
> - SONY YAY
> - DreamWorks Kids
> - Nick Jr.
> - CBeebies
> - Nickelodeon
> - Boomerang
> - Rock Extreme
> - BBC Earth
> - Love Nature 4K
> - BBC Lifestyle
> - Luxe TV
> - Dunia Sinema
> - tvN Movies
> - Zee Thirai
> - Colors Cineplex
> - CinemaWorld
> - BBC World News
> - Al Jazeera HD
> - CGTN
> - CNA
> - EuroNews
> - WION
> - Parlimen Malaysia
> - ABC Australia
> - DW English
> - NHK World Japan
> - France 24
> - tvN
> - Paramount Network
> - WBTV
> - Rock Entertainment
> - MTV Live
> - Colors HD Tamil
> - 8TV
> - Now Jelli
> - CCTV4
> - SET International
> - TV1
> - TV2
> - TV3
> - Didik TV
> - TV9
> - Salam HD
> - TV Alhijrah
> - Sensasi
> - Inspirasi
> - Degup
> - Dunia Sinema
> - Pesona
> - Laku Mall

## RTM Klik
From now on, RTM Klik EPG data will be using channel names as XMLTV ID. These channels have EPG data:
> - TV1
> - TV2
> - Okey
> - Sukan RTM
> - Bertia RTM
> - TV6
> - Dewan Rakyat
> - Dewan Negara
> - Radio Klask
> - Nasional FM
> - Traxx FM
> - AI FM
> - Minnal FM
> - Asyik FM
> - Selangor FM
> - SabahV FM
> - Sarawak FM
> - Labuan FM
> - Kedah FM
> - KL FM
> - Kelantan FM
> - Terengganu FM
> - Pahang FM
> - Johor FM
> - Negeri FM
> - Negeri FM
> - Perak FM
> - Mutiara FM
> - Perlis FM
> - Melaka FM
> - Sabah FM
> - Wai FM
> - Red FM
> - Langkawi FM
> - Limbang FM
> - Miri FM
> - Sri Aman FM
> - Bintulu FM
> - Sibu FM
> - Sandakan FM
> - Tawau FM
> - Keningau FM

## MYTV Broadcasting
The XMLTV ID is the channel number itself, for example: `101` is the Channel ID for `TV1`.

# Extras
No information available for any of your channels? Change the XMLTV ID to CHN to display a "Channel Information Not Available" notice on your EPG guide.
