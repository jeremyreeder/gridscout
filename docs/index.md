---
layout: default
title: GridScout™
permalink: /
---

GridScout™ is the console-based map-search tool that you didn't know you
needed. It can help you make better use of your paper maps. Without it, the
process of finding and marking places of interest is tedious. Let GridScout™
solve that so you can get on with your duty of planning for the impending
apocalypse, or whatever it is that you do.

# Suggested workflow
1. Order waterproof paper maps of your areas of interest. Have them printed
with an MGRS (aka USNG) or UTM grid.
2. Get some [clear plastic overlays][duralar].
3. Search for points of interest by category: "power plants", "tank farms",
"distribution centers", etc.
4. Select individual results to see aerial and street-level views as needed.
5. Edit the GridScout™ search log (log/gridscout.log), removing any irrelevant
search results.
6. Using either the search log or the console output as a reference, plot
points on the overlays.
7. File the search log away for future reference.

# What, no GUI?
For its primary purpose of bulk collection of MGRS coordinates, simple text
output works well. But GridScout™ does integrate with
[Gmap4][gmap4] to give aerial views in your web browser. From there, you can
access other online resources such as topographic and street-level views.
Strictly speaking, however, these are not part of GridScout™.

# Seriously, paper maps?
Going into battle dependent on vulnerable infrastructure is unwise. So yes,
actual printed maps and overlays are advantageous. They work independently of
power and communication grids. They're durable, highly portable, and
low-maintenance. Fancy technology has its place, but printed maps excel in the
field. With GridScout™, you can apply the technology without the
vulnerabilities. That is, it puts your computer and the Internet to good use
now, and it helps you record on more durable media the information that yo'll
need later.

# Why MGRS coordinates?
The [Military Grid Reference System][mgrs] is a whole-world variant of the
UTM coordinate system. It's used by NATO militaries because it's concise,
minimizes distortion, and makes for easy math. Latitude and longitude are
greatly lacking in these qualities. Map vendors such as [MyTopo][mytopo] allow
you to have your maps printed with a UTM grid, and for the aforementioned
reasons I suggest that you take them up on that option.

# How do I get GridScout™?
It's on [GitHub][github], and it's free!

# Are my searches secure?
Searches go through Google. They are encrypted so that only you and Google can
read them. They're associated with whatever Google account you choose to use
when you create a key for Google's API. If you require complete anonymity, then
create a Google account that is not associated in any way with your actual
identity. Then access it only from public locations like libraries and coffee
shops, and only while wearing a mask; or use Tor, which will conceal your
location with less trouble. Lastly, when setting your base location, don't use
your exact actual location unless you're okay with Google knowing it. Truncate
your coordinates to 10-kilometer precision if you like, or set a base location
on the other side of town; your search results won't be drastically affected.

Aerial views are done through [Gmap4][gmap4], a service of
_mappingsupport.com_. The MGRS coordinate of any place that you choose to view
is shared with _mappingsupport.com_ in an encrypted manner.

# How can I learn more about community intelligence?
Read [SHTF Intelligence: An Intelligence Analyst's Guide to Community
Intelligence][shtf-intel].


[duralar]:    https://smile.amazon.com/gp/product/B0015LWRZY
[github]:     https://github.com/jeremyreeder/gridscout
[gmap4]:      https://mappingsupport.com/p/gmap4-free-online-topo-maps.html
[mgrs]:       https://en.wikipedia.org/wiki/Military_Grid_Reference_System
[mytopo]:     https://www.mytopo.com
[shtf-intel]: https://forwardobserver.com/product/community-intelligence-program-print-version/
