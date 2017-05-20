---
layout: post
title: "Ruby Computers"
date:   2016-05-31 23:28:39 +0300
author: "theo"
categories: blog
tags: [blog]
permalink: /blog/ruby-computers
---

When I was trying to come up with a gameplay hook for Ruby: Dark Influence (henceforth referred to as RDI), I came up with the idea of having Computers that change things in the environment of the game.

Obviously this idea had been done before, but "nothing is original" (tm) so I set out to do it anyway.

My first implementation was created when I was still quite novice in the dark magic of Unity.

![The first implementation of Computers in Ruby: Dark Influence]({{ site.url }}/images/blog/ruby-computers/old-computer.jpg)

*The first implementation of Computers in Ruby: Dark Influence*

It relied on tons upon tons of hacks and threw out exceptions all the time that I had no idea how to deal with.

That's when I figured I could re-write it, and not only that, but make it much more graphically appealing too.

![The current implementation of Computers in Ruby: Dark Influence]({{ site.url }}/images/blog/ruby-computers/new-computer.jpg)

*The current implementation of Computers in Ruby: Dark Influence*

It looks pretty, but I'm now torn on whether players should be forced to "bash" their way out of the game's puzzles.

The other day I saw my brother playing Second Sight on the PS2, developed by Free Radical (who went on to create the Timesplitters series).

Second Sight had a pretty complex but intuitive in-game computer system, which had a lot of features I had already thought up for RDI, such as watching a live camera feed from an actual camera inside the level.

![Computers in Second Sight]({{ site.url }}/images/blog/ruby-computers/second-sight.jpg)

*photo taken from [This YouTube playthrough of Second Sight on PS2](https://www.youtube.com/watch?v=0GBYOq6XawM)*

At first I was shocked that a game from 2004 had such a well-built in-game computer system and felt devastated that my brilliant idea had aleady been made, and much better than I would have implemented it myself.

That didn't stop me from working on it, though. I plan on the next iteration to have more of a graphical interface (like Second Sight) but I will leave the terminal in for nerds like me (and perhaps make it necessary for more difficult modes of the game).

Thanks, Second Sight!


