---
layout: default
title: GridScout™
permalink: /
---


GridScout™ is the console-based Google Maps search tool that you didn't know
you needed. It'll help you make better use of your paper maps. Without it, the
process of finding and marking places of interest is tedious. Let GridScout™
solve that so you can get on with your duty of planning for the impending
apocalypse, or whatever it is that you do.

![Screenshot of a GridScout™ search for newspaper
publishers](images/search-screenshot.png)

As you can see, it's a tool for bulk collection of location data, including
MGRS coordinates, to be used by intelligence analysts. Finally, MGRS search for
Google Maps!

# Suggested workflow
1. Order [waterproof paper maps][mytopo] of your areas of interest. Have them
printed with an MGRS (aka USNG) or UTM grid.
2. Get some [clear plastic overlays][duralar].
3. Search for points of interest: "power plant", "tank farm", "distribution
center", etc.
4. Select individual results to see aerial and street-level views as needed.
5. Edit the GridScout™ search log (log/gridscout.log), removing any irrelevant
search results.
6. Using either the search log or the console output as a reference, plot
points on the overlays.
7. File the search log away for future reference.

# What, no GUI?
For its primary purpose of bulk collection of MGRS coordinates, simple text
output in a terminal works well. But GridScout™ does integrate with
[GISsurfer][gis-surfer] to give aerial views in your web browser. From
there, you can easily access other online resources such as topographic and
street-map views. Strictly speaking, however, these are not part of GridScout™.

![Sceenshot of a GridScout™ aerial view of a petroleum
refinery](images/aerial-screenshot.png)

# Seriously, paper maps?
Going into battle dependent on vulnerable infrastructure is unwise. So yes,
actual printed maps and overlays are advantageous. They work independently of
power and communication grids. They're durable, highly portable, and
low-maintenance. Fancy technology has its place, but printed maps excel in the
field. With GridScout™, you can apply the technology without the
vulnerabilities. That is, it puts your computer and the Internet to good use
now, and it helps you record on more durable media the information that you'll
need later.

# Why MGRS coordinates?
The [Military Grid Reference System][mgrs] is a whole-world variant of the
UTM coordinate system. It's used by NATO militaries because it's concise,
minimizes distortion, and makes for easy math. Latitude and longitude are
greatly lacking in these qualities. Map vendors such as [MyTopo][mytopo] allow
you to have your maps printed with a UTM grid, and for the aforementioned
reasons I suggest that you take them up on that option.

# How do I get the GridScout™ map search tool?
It's on [GitHub][github], where you'll find installation instructions. And it's
free!

# Are my searches secure?
Searches go through Google. They are encrypted so that only you and Google can
read them. They're associated with whatever Google account you choose to use
when you create a Google Places API key. If you require complete anonymity,
then create a Google account that is not associated in any way with your actual
identity. Then use it only in public places like libraries and coffee shops,
and only while wearing a mask; or use an anonymous VPN service such as
[ProtonVPN][protonvpn] or [Tor][tor], which will conceal your location with
less trouble. Lastly, when setting your base location, don't use your exact
actual location unless you're okay with Google knowing it. Truncate your
coordinates to 10-kilometer precision if you like, or set a base location on
the other side of town; your search results won't be drastically affected.

Aerial views are accessed through [Google Maps][google-maps]. When you access
the aerial view of a location, your web browser will submit that location's
MGRS coordinate in an encrypted manner. Depending on your network and the
configuration of your browser, it may be possible for Google to determine your
actual location regardless of the base location that you used for your
searches. If this is a serious problem for you, then simply locate each search
result on your MGRS-compatible paper maps.

# Who are you, and why are you doing this?
{:#jeremy}
My name is Jeremy Reeder. Professionally, I'm a network security analyst and a
part-time [bank-vault engineer][safehouse]. I take an interest in the security
of my home and my community, so I make a point of protecting them as well. In
the past I have volunteered as a firefighter, a home security advisor, and a
range safety officer.

You may wish to protect your own home and community. I suggest that you work
together with others around you who share this goal. Such a group may be called
an emergency response team, an emergency service, a posse, or a militia. If
you're in search of ways to contribute to the defense of your own community,
I've got some [ideas][contributing].

I created the GridScout™ map search tool to help me in my role as a community
defense analyst for [my local battalion][battalion] of Idaho's unorganized
militia. I share it to help the people of other communities in the development
of their own defense intelligence. I write occasionally on this and other manly
topics as my manliness directs me.

You can reach me at [jeremy@gridscout.net][jeremy]. To encrypt the
conversation, use [ProtonMail][protonmail] or an OpenPGP-based email client.
Here's my [public key][jeremy-key].

# How can I learn more about defense intelligence?
Read [SHTF Intelligence: An Intelligence Analyst's Guide to Community
Intelligence][shtf-intel], by Samuel Culper. It'll teach you the following:
- Intelligence goals — tactical, operational, & strategic
- How to organize an intelligence team
- How to plan intelligence operations
- What to look for and how to find it — OSINT, HUMINT, & COMINT
- How to use map overlays for location intelligence — planning, battletracking,
  & reporting
- How to generate useful intel reports — INTSUM, ORBAT, & SITTEMP

For an overview of the topic, including some good examples of how your maps and
map-related information could come in very handy, read the article [How to
Build an Area Study for Emergencies and Community Security][area-study],
courtesy of [Forward Observer][forward-observer].

# Blog
[GridScout™ Blog][blog] is dedicated to the proficient defensive use of MGRS
maps, GridScout™, and other tools well suited to the goals of GridScout™.

# Legal notice
Site icon, made by [Freepik][freepik] from [flaticon.com][flaticon], is
licensed under [Creative Commons BY 3.0][icon-license].

All other content © 2018 Jeremy Reeder. Use and distribution are subject to the
terms of the [MIT License][mit-license].


[area-study]:       https://forwardobserver.com/how-to-build-an-area-study-for-emergencies-and-community-security/
[battalion]:        https://adacountylightfoot.github.io
[blog]:             blog/
[contributing]:     contributing
[duralar]:          https://smile.amazon.com/gp/product/B0015LWRZY
[github]:           https://github.com/jeremyreeder/gridscout/blob/master/README.md
[freepik]:          https://www.freepik.com
[flaticon]:         https://www.flaticon.com
[forward-observer]: https://forwardobserver.com
[gis-surfer]:       https://gissurfer.com
[icon-license]:     http://creativecommons.org/licenses/by/3.0
[jeremy]:           mailto:jeremy@gridscout.net
[jeremy-key]:       publickey.jeremy@gridscout.net.asc
[mgrs]:             https://en.wikipedia.org/wiki/Military_Grid_Reference_System
[mit-license]:      https://github.com/jeremyreeder/gridscout/blob/master/LICENSE.md
[mytopo]:           https://www.mytopo.com
[protonmail]:       https://protonmail.com
[protonvpn]:        https://protonvpn.com
[safehouse]:        https://www.thesafehouse.info/
[shtf-intel]:       https://forwardobserver.com/product/community-intelligence-program-print-version/
[tor]:              https://en.wikipedia.org/wiki/Tor_(anonymity_network)
