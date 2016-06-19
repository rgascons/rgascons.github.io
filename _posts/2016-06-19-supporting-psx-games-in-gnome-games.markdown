---
layout: post
title:  "Supporting PSX games in Gnome Games"
date:   2016-06-19 12:00:00 +02:00
categories: gsoc
---
Nearly one month into the GSoC program and things are only getting more exciting.
It's been a busy and interesting month and I've made a lot of progress into
supporting multi-disk games. The first step however, is offering support to PSX games
which is the main platform with games having multiple disks.

The emulator we're porting is called [pcsx_rearmed](https://github.com/libretro/pcsx_rearmed)
which is an ARM oriented emulator, capable of recompiling MIPS->ARM instructions. It's used
in a lot of Android apps and other ancient devices and have a good reputation among this
community.

In gnome-games however, we encountered and error which caused an seg-fault when loading
games. After investigating the source code and search for clues of what could happen
inside the emulator, another programmer appeared who claimed he could know what the
problem was and how to fix it. Luckily, my mentor and him live in the _same city_, which
accelerated things a lot. Right now, the code appears to have been fixed.

Next update about GSoC will hopefully talk about UI design and the multi-disk support
core functionalities.
