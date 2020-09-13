---
layout: post
title: Solar navigation with an analog watch
author: Jeremy Reeder
date: 2020-09-09
tags: compass watch sundial
redirect_from:
  - /watch-navigation
  - /reverse-sundial
---

You probably already know some basic solar navigation:
- The sun rises in the east and sets in the west.
- The sun is directly south at noon.

But these are only rough approximations of the truth. And they can be plenty
misleading, so let's just call them LIES. Here I present _actual_ truths about
the position of the sun and a sometimes better way to find directions. No
equipment necessary except an analog watch.

### Lie #1: The sun rises in the east and sets in the west.

At my home near the 43<sup>rd</sup> parallel, trusting that the sun rises in
the east can mislead a fella by up to 34° in winter and summer. It's even less
accurate at higher latitudes. Here's the truth:

The sun rises approximately in the east and sets approximately in the west.
Twice a year, at the equinoxes, any deviation from due east and due west is
negligible.  But the sun deviates northward in both rising and setting as we
approach the June solstice.  And it deviates southward as we approach the
December solstice.  At each solstice you'll get at least 25° of deviation,
depending on your latitude.  Inside the polar circles, the sun won't actually
rise or set at all, it'll only circle around you just above or below the
horizon.
{:.indent}

### Lie #2: The sun is directly south at noon.

Yeah, okay, but when is noon? Do you trust the government to tell you? They may
mislead you by an hour or two. Local solar noon may not come at 12:00 civil
time. It varies with your longitudinal position within the time zone, and
daylight saving time moves it an hour clockwise. Today my solar noon is at
1:42pm.

Don't forget, of course, that in parts of the world the sun is _north_ at solar
noon. And in the tropics, it alternates.

## How 'bout a reverse sundial?

The hour hand of an analog watch follows the apparent path of the sun pretty
closely at moderate to high latitudes. So when the sun is visible and you're at
least 20° of latitude away from the sun's path, it comes in pretty handy as a
compass.

### Navigating with a 12-hour dial
- When you're north of the sun's path and the hour hand of a 12-hour watch dial on a horizontal plane is pointed at the sun, south is about halfway between it and the dial's solar noon position.
- When you're south of the sun's path and the solar noon position on a 12-hour watch dial is pointed at the sun, north is about halfway between it and the hour hand.
- When the sun is high in the sky, it helps to hold a small pole (such as a pen) vertically next to your watch and align the hour hand with its shadow.
- NOTE: Navigation is easier with a _24-hour_ dial.

If you're not sure when your local solar noon is, then calculate it or look it
up. Or at least, for crying out loud, don't use the 12:00 position during
daylight saving time! Instead, use 1:00 in summertime to compensate for DST.
{:.tangent}

### Navigating with a 24-hour dial
- When you're north of the sun's path and the hour hand of a 24-hour watch dial on a horizontal plane is pointed at the sun, the dial's solar noon position points approximately southward.
- When you're south of the sun's path and the solar noon position of a 24-hour watch dial on a horizontal plane is pointed at the sun, the hour hand points approximately northward.
- The hour hand on a 24-hour dial revolves only once per day, matching the sun. Hence these simplified methods that don't require bisection of angles.
- These methods are easiest with daytime at the top of the dial and nighttime at the bottom, as is common in Russian military watches.

<div class="gallery" markdown="1">
![][russian-watch-photo]
*Raketa Sputnik -- a 24-hour watch from St Petersburg*
{:.indent}
</div>

### How accurate is watch-based navigation?

These methods have no error at solar noon, nor at solar midnight. Any error _before_ solar noon is always eastward. Any error _after_ solar noon is always westward.

Six hours before or after solar noon, I've observed an error at the equator equal to the declination of the sun. It decreases as my latitude increases. So this error is worst at either solstice, when it's about 23° at the equator or 17° in southern Idaho.

error<sub>0600</sub> = cos(latitude) × declination<sub>sun</sub> ?

Error at odd intervals of 3 hours from solar noon seems to be at its greatest when the declination of the sun approaches your latitude. At its worst, this means a 45° error in the tropics on those days when the sun passes directly over your head. Outside of the tropics, it means a milder peak at the summer solstice. I'm still working out exactly how much error I can expect at a given latitudinal distance from the sun's path at these intervals.

Watch-based navigation seems particularly well suited for a summertime polar expedition, where the sun is usually up and error is minimal. Who wants to come with me?

DISCLAIMER: My understanding may be imperfect. I'm fairly new at this.
{:.tangent}


[russian-watch-photo]: {{ '/images/raketa-sputnik-watch.jpg' | prepend: site.url }}