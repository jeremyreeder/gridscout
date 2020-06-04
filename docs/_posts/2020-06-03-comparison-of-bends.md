---
layout: post
title: Comparison of bends
author: Jeremy Reeder
date: 2020-06-03
tags: knot
redirect_from: /bends
---

### Experiment

I've been wondering about the relative security of various bend knots. By this
I mean how much force each knot can take before coming untied. So I did a
little experiment with eight bends tied in greased fishing line. I used this
material in order to reduce the expected force limits to a level manageable for
my testing. Having no fancy testing apparatus, I simply suspended a bag from
the fishing line and loaded the bag with stuff until the line broke.

A related measure is how much each knot reduces the breaking strength of the
ropes in which it is tied. That's not what I'm trying to measure here. That's
why I chose a material that's intentionally super slippery, hoping that in most
cases I'd reach the security limit before I reach the strength limit. But alas,
some knots just won't slip.


### Results

| Bend Knot                                | Limit (g) | Failure |
|------------------------------------------|-----------|---------|
| [Butterfly bend][butterfly-bend]         | 3056      | Break   |
| [Simple-Simon under][simple-simon-under] | 2721      | Break   |
| Simple-Simon crossover                   | 2214      | Slip    |
| Simple-Simon over                        | 1982      | Slip    |
| Simple-Simon double                      | 1933      | Break   |
| [Zeppelin bend][zeppelin-bend]           | 1827      | Break   |
| Sheetbend                                | 1089      | Slip    |
| Double sheetbend                         | 891       | Slip    |


### Conclusions

I like the butterfly bend and find it easy to tie, so I'm happy to confirm that
it holds so well. I'm surprised that the zeppelin did so much worse. I find it
a bit harder to tie and less versatile, so I may stop bothering with it.

The Simple-Simon-crossover bend is my own invention. In this test it
outperformed all but one of Harry Asher's Simple-Simon knots. Since it's also
the easiest Simple-Simon to tie, this is pretty satisfying. I had hoped,
though, that it would equal the security of the Simple-Simon-under. Maybe not
quite. Surprisingly, it looks like Asher's Simple-Simon-double substantially
reduces breaking strength, making it the worst performer of the series.

As expected, the sheetbend and double sheetbend slipped way too easily to be
worth using. What's surprising is that the double sheetbend actually did the
worst of these two.


### Tying the Simple-Simon-crossover bend

This new knot is a variant of the Simple-Simon-over that varies only in
swapping the standing part and working end of the first rope's bight around
which the second rope is tied. This results in a bight clamped identically to
that of the Simple-Simon-under bend without the added difficulty of making a
pass _under_ the rope as the -under variant requires. Uniquely among the
Simple-Simon knots, the rope ends are ultimately diagonal from each other.

![][simple-simon-crossover-photo]
*Simple-Simon crossover*


[simple-simon-crossover-photo]: {{ '/images/simple-simon-crossover-bend.jpg' | prepend: site.url }}

[butterfly-bend]:     https://www.netknots.com/rope_knots/alpine-butterfly-bend
[simple-simon-under]: https://en.wikipedia.org/wiki/Simple_Simon_under
[zeppelin-bend]:      https://www.netknots.com/rope_knots/zeppelin-bend
