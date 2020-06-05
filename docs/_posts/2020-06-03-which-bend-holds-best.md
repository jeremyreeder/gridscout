---
layout: post
title: Which bend holds best?
author: Jeremy Reeder
date: 2020-06-03
tags: knot
redirect_from:
  - /bends
  - 2020/06/03/comparison-of-bends.html
---

### Experiment

A "bend" is a knot for joining two ropes together. Thinking that it would be
helpful to know which bends do this job best, I took eight pieces of my
daughter's fishing line and did a little experiment.

In each piece I tied a different bend, which I greased before pulling it tight.
I then hung the resulting loop on a hook and suspended a bag from it. I filled
the bag with screwdrivers and wrenches and stuff, till the fishing line either
broke or slipped to a completely untied state.

I was most interested in measuring the "security", or resistance to slipping,
as opposed to breaking strength. That's why I intentionally chose the
slipperiest material available to me. I hoped that all eight lines would slip
before having a chance to break; but alas, some knots just won't slip.


### Results

| Bend Knot                                        | Limit (kg) | Failure |
|--------------------------------------------------|------------|---------|
| [Butterfly bend][butterfly-bend]                 | 6.1        | Break   |
| [Simple-Simon under][simple-simon-under]         | 5.4        | Break   |
| [Simple-Simon crossover][simple-simon-crossover] | 4.4        | Slip    |
| [Simple-Simon over][simple-simon-over]           | 4.0        | Slip    |
| [Simple-Simon double][simple-simon-double]       | 3.9        | Break*  |
| [Zeppelin bend][zeppelin-bend]                   | 3.7        | Break*  |
| [Sheetbend][sheetbend]                           | 2.2        | Slip    |
| [Double sheetbend][sheetbend-double]             | 1.8        | Slip    |

\* It's astonishing that the almighty zeppelin bend broke so much more easily
than the butterfly bend, and that the Simple-Simon-double bend, supposedly the
most secure of the Simple Simons, broke before it had a chance to show off its
grip. Further testing is needed.
{:.tangent}


### Conclusions

I like the butterfly bend and find it easy to tie, so I'm happy to confirm that
it holds so well.

The Simple-Simon-crossover bend is my own invention. In this test it
outperformed the Simple-Simon-over on which it is based. Since it's no harder
to tie, this is fairly satisfying. I had hoped, though, that it would equal the
security of the Simple-Simon-under. Maybe not.

As expected, the sheetbend and double sheetbend slipped way too easily to be
worth using. What's surprising is that the double sheetbend actually did the
worst of these two.


### Simple-Simon-crossover bend
{:#simple-simon-crossover}

This new knot is a variant of the Simple-Simon-over that varies only in
swapping the standing part and working end of the first rope's bight around
which the second rope is tied. This results in a bight clamped identically to
that of the Simple-Simon-under bend without the added difficulty of making a
pass _under_ the rope as the -under variant requires. For this reason, I
hypothesized (incorrectly, it seems) that this bend would be just as secure as the
Simple-Simon-under. Uniquely among the Simple-Simon knots, the rope ends are
ultimately diagonal from each other.

![][simple-simon-crossover-photo]
*Simple-Simon crossover*


[simple-simon-crossover-photo]: {{ '/images/simple-simon-crossover-bend.jpg' | prepend: site.url }}

[butterfly-bend]:         https://www.netknots.com/rope_knots/alpine-butterfly-bend
[sheetbend]:              https://en.wikipedia.org/wiki/Sheet_bend
[sheetbend-double]:       https://en.wikipedia.org/wiki/Sheet_bend#Double_sheet_bend
[simple-simon-crossover]: #simple-simon-crossover
[simple-simon-double]:    https://www.youtube.com/watch?v=rzz74SBDtBA
[simple-simon-over]:      https://korpegard.se/knot/?knot=22
[simple-simon-under]:     https://en.wikipedia.org/wiki/Simple_Simon_under
[zeppelin-bend]:          https://www.netknots.com/rope_knots/zeppelin-bend
