---
layout: post
title: Solar navigation with analog watch & pocket knife
author: Jeremy Reeder
date: 2020-09-09
tags: compass watch sundial
redirect_from:
  - /watch-navigation
  - /reverse-sundial
---

TL;DR -- A Russian-style 24-hour watch, aligned with the equatorial plane,
makes a fantastic solar compass.
{:.tangent .indent}

You probably already know some basic solar navigation, but these are only
rough approximations of the truth.
- The sun rises in the east and sets in the west.
- The sun is directly south at noon.

These approximations can be plenty misleading, so let's just call them LIES.
Here I present _actual_ truths about the position of the sun and a far better
way to use it to find directions. No equipment necessary except an analog
watch and a pocket knife.

### Lie #1: The sun rises in the east and sets in the west.

At my home near the 43<sup>rd</sup> parallel, trusting that the sun rises in
the east can mislead a fella by up to 34° in winter and summer. It's even less
accurate at higher latitudes. Here's the truth:

The sun rises approximately in the east and sets approximately in the west.
Twice a year, at the equinoxes, any deviation from due east and due west is
negligible. But the sun deviates northward in both rising and setting as we
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
so it comes in pretty handy as a compass. With a little trickery, even a
12-hour watch will do.

First you'll have to identify your local solar noon. Calculate it or look it
up. Use 12:00 as a rough approximation _if you must_, or 13:00 during daylight
saving time.

Next, you'll set up your watch as a _reverse equatorial sundial_ and pivot your
body till the sundial reads the correct time. When it does, you'll either know
that you're facing south or that you're facing north. Whereas sundials are
usually aligned with the north-south line and then used to determine the
current time, they work equally well in reverse.

Read on to find out how to navigate with an analog watch and a pocket knife.
{:.tangent}

### Navigating with a 24-hour dial

Navigation is easiest with daytime at the top of the dial and nighttime at the
bottom, as is common in Russian military watches. This arrangement generally
allows you to navigate without removing the watch from your wrist.

<div class="gallery" markdown="1">
![][russian-watch-photo]
*Raketa Sputnik -- a 24-hour watch from St Petersburg*
{:.indent}
</div>

#### (when north of the sun's path or directly on it)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, with the solar noon position at the top.
2. Rotate your body till the hour hand points at the sun.<sup>2</sup>
3. The dial's solar noon position now points southward<sup>3</sup>.

<sup>1</sup> Start vertical and tilt the dial away from you by an angle equal
to your latitude.
{:.tangent .indent}

<sup>2</sup> When the sun is north of the equator, you can use a knife blade to
cast a shadow on the hour hand as an alignment guide.
{:.tangent .indent}

<sup>3</sup> In the tropics, the sun may pass directly overhead at solar noon.
If it does, all directions will seem to be south. Wait ten minutes.
{:.tangent .indent}

#### (when south of the sun's path)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, with the hour hand at the top.
2. Rotate your body till the solar noon position points at the sun.<sup>4</sup>
3. The hour hand now points southward.

<sup>1</sup> Start vertical and tilt the dial away from you by an angle equal
to your latitude.
{:.tangent .indent}

<sup>4</sup> When the sun is south of the equator, you can use a knife blade to
cast a shadow on the solar-noon position as an alignment guide.
{:.tangent .indent}

### Navigating with a 12-hour dial

Remember, it's easier with a 24-hour dial. If you dislike bisecting angles or
need an excuse to go watch-shopping, keep that in mind.  {:.tangent}

#### (when north of the sun's path or directly on it)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, with the solar noon position at the top.
2. Rotate your body till the sun is halfway between the hour hand and solar noon.<sup>5</sup>
3. The dial's solar noon position now points southward<sup>3</sup>.

<sup>5</sup> When the sun is north of the equator, you can use a knife blade to
cast a shadow on the dial as an alignment guide.
{:.tangent .indent}

#### (when south of the sun's path)
1. Align the face of the dial with the equatorial plane<sup>1</sup>, and rotate it so that the position halfway between the hour hand and solar noon is at the top.
2. Rotate your body till the solar-noon position points at the sun.<sup>4</sup>
3. The top of the dial now points northward.

### How accurate is watch-based navigation?

The accuracy of this _reverse equatorial sundial_ depends primarily on your
identification of local solar noon and the alignment of your watch dial with
the equatorial plane.

#### Solar noon error

Using civil noon rather than today's local solar noon can introduce up to [30°
of error][civil-time-error]. You're often within 8°, but some localities fudge
the time more than others.

Add another 15° if you forget to compensate for daylight saving time in the
summer.

#### Equatorial-alignment error

Holding your watch horizontally<sup>6</sup> like an amateur can add up to 45°
of error at the edges of the tropics, or 21° in southern Idaho.<sup>7</sup> But
if you can hold it within 9° of correct equatorial alignment, a goal easily met
by eyeball, then your maximum error due to equatorial misalignment shrinks to
just 3°.

<sup>6</sup> Other instruction on navigating with a watch assumes that equally
spaced markings are suitable for a _horizontal_ sundial. I'm right and [they're
wrong][bicevskis-error].
{:.tangent}

<sup>7</sup> This error peaks on the summer solstice, eastward three hours before solar noon
and westward three hours after.
{:.tangent}

### Where to, then?

Although useful anywhere with sun, watch-based navigation is _particularly_
well suited for a summertime polar expedition. The sun is up all day, the
equatorial plane is conveniently near horizontal, and the sun is on the right
side of it to cast a knife-blade shadow on your dial. Handy, since magnetic
compasses are [useless][compass-failure] inside the polar circles.


[russian-watch-photo]: {{ '/images/raketa-sputnik-watch.jpg' | prepend: site.url }}

[bicevskis-error]:  http://www.wildwoodsurvival.com/survival/navigation/rbsolarnav/index.html
[civil-time-error]: http://blog.poormansmath.net/how-much-is-time-wrong-around-the-world
[compass-failure]:  https://cultofsea.com/general/using-magnetic-compass-in-polar-regions/
