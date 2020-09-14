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
13:42.

Don't forget, of course, that in parts of the world the sun is _north_ at solar
noon. And in the tropics, it alternates.

## How 'bout a reverse sundial?

The hour hand of a 24-hour analog watch follows the apparent path of the sun,
so it comes in pretty handy as a compass. With the addition of an
angle-bisection step, even a 12-hour watch will do.

First you'll have to identify your local solar noon. Calculate it or look it
up. Use 12:00 as a rough approximation if you must, or 13:00 during daylight
saving time.
{:.tangent}


### Navigating with a 24-hour dial

Note that it's easiest with daytime at the top of the dial and nighttime at the
bottom, as is common in Russian military watches. This arrangement generally
allows you to navigate without removing the watch from your wrist.

<div class="gallery" markdown="1">
![][russian-watch-photo]
*Raketa Sputnik -- a 24-hour watch from St Petersburg*
{:.indent}
</div>


#### (when north of the sun's path)
1. Align the face of the dial with the equatorial plane, with the solar noon position at the top.<sup>*</sup>
2. Rotate your body till the hour hand points directly at the sun.
3. The dial's solar noon position now points southward.

<sup>*</sup> Start vertical and tilt the dial away from you by an angle equal to your latitude.
{:.tangent .indent}

#### (when south of the sun's path)
1. Align the face of the dial with the equatorial plane, with the hour hand at the top.
2. Rotate your body till the solar noon position points directly at the sun.
3. The hour hand now points southward.

### Navigating with a 12-hour dial

#### (when north of the sun's path)
1. Align the face of the dial with the equatorial plane, with the solar noon position at the top.
2. Rotate your body till the sun is halfway between the hour hand and solar noon.
3. The dial's solar noon position now points southward.

#### (when south of the sun's path)
1. Align the face of the dial with the equatorial plane, and rotate it so that the position halfway between the hour hand and solar noon is at the top.
2. Rotate your body till the solar-noon position points directly at the sun.
3. The top of the dial now points northward.

### How accurate is watch-based navigation?

Accuracy of these methods depends on the following:

- Identification of local solar noon

Using civil noon rather than solar noon can introduce up to 12° of error, or 27°
during daylight saving time.
{:.tangent .indent}

- Alignment of the watch with the equatorial plane

Holding the watch horizontally adds up to 45° of error at the equator, or 17°
in southern Idaho. This error peaks westward at 09:00 and eastward at 15:00
solar time.
{:.tangent .indent}

Watch-based navigation seems particularly well suited for a summertime polar
expedition, where the sun's always up and the equatorial plane is conveniently
aligned pretty well with the horizontal plane. Who wants to come with me?


[russian-watch-photo]: {{ '/images/raketa-sputnik-watch.jpg' | prepend: site.url }}
