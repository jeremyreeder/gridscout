---
layout: post
title:  "Search Google Maps from the terminal, get results in MGRS"
date:   2018-05-09 22:00:00 -0600
categories: gridscout mgrs google maps overlays
---
GridScout™ is a console-based alternative interface for searching Google Maps.
Rather than displaying results graphically, it outputs a concise list of search
results, along with MGRS coordinates.

This interface is convenient for bulk collection of location data. For example,
an intelligence analyst could use this tool to create a list of distribution
centers, antenna farms, and other critical infrastructure. Such a list is
useful in the preparation of plastic map overlays for community defense
planning.

# Plastic overlays? You mean, like, for real paper maps?
Yes, it is advantageous in certain situations to minimize dependence on
infrastructure. Large physical maps and overlays work independently of the
power and communication grids; and they're more easily transported than
computers, large LCD screens, and generators.

# Why MGRS coordinates?
The [Military Grid Reference System][mgrs] is a whole-world variant of the
UTM coordinate system. It's used by NATO militaries because it's concise,
minimizes distortion, and makes for easy math. Latitude and longitude are
greatly lacking in these qualities. Map vendors such as [MyTopo][mytopo] allow
you to have your maps printed with a UTM grid, and for the aforementioned
reasons I suggest that you take them up on that option.

To get GridScout™, go to [GitHub][github].

[mgrs]:   https://en.wikipedia.org/wiki/Military_Grid_Reference_System
[mytopo]: https://www.mytopo.com
[github]: https://github.com/jeremyreeder/gridscout
