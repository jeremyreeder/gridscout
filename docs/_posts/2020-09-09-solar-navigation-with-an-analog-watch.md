---
layout: post
title: Solar navigation with an analog watch
author: Jeremy Reeder
date: 2020-09-09
tags: knot
---

You probably already know some basic solar navigation:
- The sun rises in the east and sets in the west.
- The sun is directly south at noon.

But these are only rough approximations of the truth. And they can be plenty
misleading, so let's just call them lies. Here I present _actual_ truths about
the position of the sun and a better way to find directions. No equipment
necessary except an analog watch.

## Lie #1: The sun rises in the east and sets in the west.

At my home near the 43rd parallel, trusting that the sun rises in the east can
mislead a fella by up to 34 degrees in winter and summer. It's even less
accurate at higher latitudes. Here's the truth:

The sun rises approximately in the east and sets approximately in the west.
Twice a year, at the equinoxes, any deviation from due east and due west is negligible.
The sun deviates northward in both rising and setting as we approach the June solstice.
It deviates southward as we approach the December solstice.
The deviation increases at higher latitudes.
Around the summer solstice in or near a polar circle, the sun may not set at all.
{:.indent}

## Lie #2: The sun is directly south at noon.

Yeah, okay, but when is noon? Do you trust the government to tell you? They may
mislead you by an hour or two. Local solar noon may not come at 12:00 civil
time. It varies with your longitudinal position within the time zone, and
daylight saving time moves it an hour clockwise. Today my solar noon is at
1:42pm.

## Navigating with a 12-hour dial
- When you're north of the sun's path and the hour hand of a 12-hour watch dial on a horizontal plane is pointed at the sun, south is halfway between it and the dial's local solar noon position.
- When you're south of the sun's path and the local solar noon position on a 12-hour watch dial is pointed at the sun, north is halfway between it and the hour hand.
- When the sun is high in the sky, it helps to hold a small pole (such as a pen) vertically next to your watch and align the hour hand with its shadow.
- At sunrise and sunset, these methods produce only a third of the error given by the basic methods. At local solar noon, they produce no error at all.
- Navigation is easier with a _24-hour_ dial.

## Navigating with a 24-hour dial
- When you're north of the sun's path and the hour hand of a 24-hour watch dial on a horizontal plane is pointed at the sun, the dial's local solar noon position points approximately southward.
- When you're south of the sun's path and the local solar noon position of a 24-hour watch dial on a horizontal plane is pointed at the sun, the hour hand points approximately northward.
- The hour hand on a 24-hour dial revolves only once per day, matching the sun. Hence these simplified methods that don't require bisection of angles.
- These methods are easiest with daytime at the top of the dial and nighttime at the bottom, as is common in Russian military watches.

<div class="gallery" markdown="1">
![][russian-watch]
*Raketa Sputnik -- a 24-hour watch from St Petersburg*
{:.indent}
</div>


[russian-watch]: {{ '/images/raketa-sputnik-watch.jpg' | prepend: site.url }}
