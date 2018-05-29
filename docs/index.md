---
layout: default
title: GridScout™
permalink: /
---

GridScout™ is a console-based map-search tool for use by community-defense
intelligence analysts. It lets them do bulk collection of location data,
including MGRS coordinates.

# Suggested workflow
1. Search for various points of interest by category: "power plants", "tank
farms", "distribution centers", etc.
2. Select individual results to see aerial and street-level views as needed.
3. Edit the GridScout™ search log (log/gridscout.log), removing any irrelevant
search results.
4. Get a paper map of the area and some clear plastic overlays.
5. Using either the search log or the console output as a reference, plot
points on the overlays.
6. File the search log away for future reference.

# What, no GUI?
For its primary purpose of bulk collection of MGRS coordinates, simple text
output works well. But GridScout™ does integrate with
[Gmap4][gmap4] to give aerial views in your web browser. From there, you can
access other online resources such as topographic and street-level views.
Strictly speaking, however, these are not part of GridScout™.

# Seriously, paper maps?
Well, I use "waterproof paper". It's technically not real made-from-trees
paper. But yes; physical maps printed on large paper-like sheets, combined with
well-made overlays, are advantageous in certain situations. They work
independently of the power and communication grids; they're durable and
low-maintenance; and they're easily transported, in contrast to large LCD
screens and generators.

# Why MGRS coordinates?
The [Military Grid Reference System][mgrs] is a whole-world variant of the
UTM coordinate system. It's used by NATO militaries because it's concise,
minimizes distortion, and makes for easy math. Latitude and longitude are
greatly lacking in these qualities. Map vendors such as [MyTopo][mytopo] allow
you to have your maps printed with a UTM grid, and for the aforementioned
reasons I suggest that you take them up on that option.

# How do I get GridScout™?
It's on [GitHub][github], and it's free!

# How can I learn more about community intelligence?
Read [SHTF Intelligence: An Intelligence Analyst's Guide to Community
Intelligence][shtf-intel].


[github]:     https://github.com/jeremyreeder/gridscout
[gmap4]:      https://mappingsupport.com/p/gmap4-free-online-topo-maps.html
[mgrs]:       https://en.wikipedia.org/wiki/Military_Grid_Reference_System
[mytopo]:     https://www.mytopo.com
[shtf-intel]: https://forwardobserver.com/product/community-intelligence-program-print-version/
