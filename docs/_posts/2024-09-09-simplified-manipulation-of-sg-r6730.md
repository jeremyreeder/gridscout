---
layout: post
title: Simplified Manipulation of Sargent & Greenleaf R6730
author: Jeremy Reeder
date: 2024-09-09
redirect_from:
  - /r6730
tags: combination lock manipulation safe safecracker
---

This is the method that I used to open a high-quality mechanical combination
lock on a good gun safe in less than an hour without damage and almost without
tools.

tl;dr -- Soft fingers can open hard locks. The right contact point is more
useful than the left. Stickers are faster than graphs.
{:.tangent}

## Overview

I opened this S&G R6730 lock by "manipulation", with the aid of a fancy
amplifier.  The amp wasn't really needed to detect the contact points, which
were easy to feel.  But it did turn out to help a great deal in stopping people
from talking to me so I could focus on my task, so I kept it in my ears.

JARGON ALERT! This is not an *introduction* to safecracking, it's an advanced
commentary. For a good introduction, see TNL's [Guide to
Manipulation][gtm-legit][.][gtm-bootleg]
{:.tangent}

Locks like this are often manipulated with the aid of several graphs on paper,
detailing all variations in left and right contact points for every trial
combination.  My first successful manipulation of an R6730 came after four and
a half hours drawing five pages of graphs. As useful as that can be in
training, it also makes the process longer and a bit tedious. When dealing with
a lock type that I'm already familiar with, I find the following alternative
much faster. I prefer to deal only with the right contact point and to use a
simplified progress-tracking system.

My reason for preferring the right contact point is this: The notch in this
lock's drive cam, being shallowly ramped on the right and more abrupt on the
left, presents a very measurable leftward movement of the right contact as we
get closer to the correct combination, usually much moreso than any rightward
movement of the left contact.

As for other simplifications to the progress-tracking system, I do away with
the graphing. Instead I fasten a pair of hairline-index stickers to the dial
and dial ring. Then I track my progress with a series of notes and iterative
realignment of the stickers.

<div class="gallery" markdown="1">
![These two stickers align at the right contact point.][dial-with-stickers]
*Stickers in Action*
</div>

With the lever nose resting on its right contact point, I place a sticker on
the dial somewhere around the one-o'clock position. That position is arbitrary
aside from being away from leaving the twelve-o'clock dialing index
unobstructed and choosing somewhere easy to see and reach. The other sticker
than goes on the dial ring in perfect alignment with that first sticker. The
dial-ring sticker is subsequently moved rightward any time a contact point
deeper within the drive cam is found, realigning it with the new contact point
associated with the new best-so-far combination.

## Notes

Here are the notes that I took during this manipulation.

The comments below each note were added afterward to clarify those notes for
instructional purposes.
{:.tangent}

- Started by dialing AWL x, where x is the range from 50 to 90 and from 0 to 40,
  in increments of 10. The best value of x was 90.

All-wheels-left to 90 produced the narrowest contact area seen so far, so we
know that the wheelpack radius under the fence is at a minimum with this
combination, compared with all other combinations tried so far.
{:.tangent .indent}

- Tried 90L-xR-90L, where x is the range from 0 to 80 in increments of 10. The
  value of x made no difference.

I chose to vary the position of wheel two first while leaving the other two the
same, because this conveniently maintains the normal direction of rotation for
parking each wheel. We see that the same contact area is produced for all
positions of wheel 2, so this wheel doesn't seem to be in contact with the
fence. It won't be until we find a value for the first or third wheel which
reduces that wheel's radius under the fence. The best combination so far is
90L-90R-90L. Let's vary a different wheel now. Varying wheel 3 will require the
least dialing, so let's do that one.
{:.tangent .indent}

- Tried 90L-90R-xL, where x is the same range as before. The best value of x was
  0.

The lowest wheelpack radius under the fence that we've witnessed so far was
with wheel 3 parked at 0L, producing a best-so-far combination of 90L-90R-0L.
Let's move on to varying wheel 1, since we haven't varied that one on its own
yet.
{:.tangent .indent}

- Tried xL-90R-0L, where x is the range from 0 to 80 in increments of 10. The
  best value of x was 80.

The lowest wheelpack radius under the fence that we've witnessed so far was
with wheel 1 parked at 80L. The best combination so far is 80L-90R-0L. Now
let's vary wheel 3 again, since it's the quickest to do. Let's do it in smaller
increments this time. Now that we've made progress with all wheels, we have a
much greater chance of finding a gate that otherwise most likely would've been
masked by the larger radius of other wheels.
{:.tangent .indent}

- Tried 80L-90R-xL, where x is the range from 1 to 99 in increments of 2. The
  best value of x was 7.

The lowest wheelpack radius under the fence that we've witnessed so far was
with wheel 3 parked at 7L. The best combination so far is 80L-90R-7L.  Now
let's vary the position of wheel 2, using slightly larger intervals for now
because it'll otherwise take a lot more time than it did for wheel 3. We'll
come back to this wheel later in smaller intervals if it proves necessary. This
isn't just a gamble, after all there's a benefit to making progress on all
wheels, and often it's not until we've found a very low-radius point on every
wheel that we're able to unmask clear gate indications on any wheel.
{:.tangent .indent}

- Tried 80L-xR-7L, where x is 95 and the range from 0 to 85 in increments of 5.
  The best value of x was 65.

The lowest wheelpack radius under the fence that we've witnessed so far was
with wheel 2 parked at 65R. The best combination so far is 80L-65R-7L.
{:.tangent .indent}

- Tried 80L-65R-xL, where x is a range starting at 9 and incrementing by 2.
  Unlocked on 80L-65R-79L.

On 80L-65R-79L, I felt the drive cam engage the fence lever when I turned the
dial to the contact area. I then rotated the dial to the right to retract the lock
bolt. This unblocked the door's boltwork, allowing me to retract it with the
door handle.
{:.tangent .indent}

It took me 50 minutes to open this lock, going slowly and methodically to
ensure accuracy but not unnecessarily slowed by a tedious textbook-style
graphing process. That's how I like to do it, and it works well for me.
Sometimes faster, when nobody bugs me. My record on this type of lock is 25
minutes.

Of course I then reset the combination, because I can't have you blokes knowing
it.


[dial-with-stickers]: {{ '/images/dial-with-hairline-index-stickers.jpg' | prepend: site.url }}

[gtm-legit]:   https://foleybelsawlocksmithing.com/products/manipulation-book
[gtm-bootleg]: https://ia800902.us.archive.org/33/items/TheNationalLocksmithGuideToManipulation/The%20National%20Locksmith%20-%20Guide%20to%20Manipulation_text.pdf
