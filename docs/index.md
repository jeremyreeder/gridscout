---
layout: default
title: GridScout Map™
permalink: /
redirect_from: /contributing
---

# GridScout Map™

This is the console-based Google Maps search tool that you didn't know you
needed. It'll help you make better use of your paper maps. Without it, the
process of finding and marking places of interest is tedious. Let GridScout
Map™ solve that so you can get on with your duty of planning for the impending
apocalypse, or whatever it is that you do.

![Screenshot of a GridScout Map™ search for newspaper
publishers](images/search-screenshot.png)

As you can see, it's a tool for bulk collection of location data, including
MGRS coordinates, to be used by intelligence analysts. Finally, MGRS search for
Google Maps!

## Suggested workflow
1. Order [waterproof paper maps][mytopo] of your areas of interest. Have them
printed with an MGRS (aka USNG) or UTM grid.
2. Get some [clear plastic overlays][duralar].
3. Search for points of interest: "power plant", "tank farm", "distribution
center", etc.
4. Select individual results to see aerial and street-level views as needed.
5. Edit the GridScout Map™ search log (log/gridscout.log), removing any
irrelevant search results.
6. Using either the search log or the console output as a reference, plot
points on the overlays.
7. File the search log away for future reference.

## What, no GUI?
For its primary purpose of bulk collection of MGRS coordinates, simple text
output in a terminal works well. But GridScout Map™ does integrate with
[GISsurfer][gis-surfer] to give aerial views in your web browser. From there,
you can easily access other online resources such as topographic and street-map
views. Strictly speaking, however, these are not part of GridScout Map™.

![Sceenshot of a GridScout Map™ aerial view of a petroleum
refinery](images/aerial-screenshot.png)

## Seriously, paper maps?
Going into battle dependent on vulnerable infrastructure is unwise. So yes,
actual printed maps and overlays are advantageous. They work independently of
power and communication grids. They're durable, highly portable, and
low-maintenance. Fancy technology has its place, but printed maps excel in the
field. With GridScout Map™, you can apply the technology without the
vulnerabilities. That is, it puts your computer and the Internet to good use
now, and it helps you record on more durable media the information that you'll
need later.

## Why MGRS coordinates?
The [Military Grid Reference System][mgrs] is a whole-world variant of the
UTM coordinate system. It's used by NATO militaries because it's concise,
minimizes distortion, and makes for easy math. Latitude and longitude are
greatly lacking in these qualities. Map vendors such as [MyTopo][mytopo] allow
you to have your maps printed with a UTM grid, and for the aforementioned
reasons I suggest that you take them up on that option.

## How do I get GridScout Map™?
It's on [GitHub][github], where you'll find installation instructions. And it's
free!

## Are my searches secure?
Searches go through Google. They are encrypted so that only you and Google can
read them. They're associated with whatever Google account you choose to use
when you create a Google Places API key. No, you can't trust Google. If a
better service can be found elsewhere, then we may ditch Google in the future.
In the meantime, if you require complete anonymity, then create a Google
account that is not associated in any way with your actual identity. Then use
it only in public places like libraries and coffee shops, and only while
wearing a mask; or use an anonymous VPN service such as [ProtonVPN][protonvpn]
or [Tor][tor], which will conceal your location with less trouble. Lastly, when
setting your base location, don't use your exact actual location unless you're
okay with Google knowing it. Truncate your coordinates to 10-kilometer
precision if you like, or set a base location on the other side of town; your
search results won't be drastically affected.

Aerial views are accessed through [GISsurfer][gis-surfer]. When you access
the aerial view of a location, your web browser will submit that location's
MGRS coordinate in an encrypted manner. Depending on your network and the
configuration of your browser, it may be possible for GISsurfer to determine
your actual location regardless of the base location that you used for your
searches. If this is a serious problem for you, then don't use the aerial view.

## Blog
Subscribe to [GridScout Gazette™][blog] to keep up on this and other manly
pursuits.

# Legal notice
Site icon, made by [Freepik][freepik] from [flaticon.com][flaticon], is
licensed under [Creative Commons BY 3.0][icon-license].

<div class="post-metadata">© 2018-2020 gridscout.net &amp; Jeremy Reeder</div>


[area-study]:       https://forwardobserver.com/how-to-build-an-area-study-for-emergencies-and-community-security/
[blog]:             gazette/
[duralar]:          https://smile.amazon.com/gp/product/B0015LWRZY
[github]:           https://github.com/jeremyreeder/gridscout/blob/master/README.md
[freepik]:          https://www.freepik.com
[flaticon]:         https://www.flaticon.com
[gis-surfer]:       https://gissurfer.com
[icon-license]:     http://creativecommons.org/licenses/by/3.0
[jeremy-key]:       publickey.jeremy@gridscout.net.asc
[mgrs]:             https://en.wikipedia.org/wiki/Military_Grid_Reference_System
[mytopo]:           https://www.mytopo.com
[protonmail]:       https://protonmail.com
[protonvpn]:        https://protonvpn.com
[safehouse]:        https://safehouse.gridscout.net/
[shtf-intel]:       https://forwardobserver.com/product/community-intelligence-program-print-version/
[tor]:              https://en.wikipedia.org/wiki/Tor_(anonymity_network)
