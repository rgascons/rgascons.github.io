---
layout: post
title:  "GSoC: final evaluation"
date:   2016-08-22 10:00:00 +02:00
categories: gsoc
---


This blog-post contains the final evaluation of my Google summer of Code 2016
project for the GNOME organization. More precisely, I've been **working in the Games
application** under the mentorship of [Adrien Plazas](https://wiki.gnome.org/AdrienPlazas)
**implementing multi-source/multi-disc games and offer support to the PlayStation platform**.
If you want to skip to the links section click [here](#links).

This task involved contributing to various repositories and perform a set of
different tasks.

## Summary

In the following list there's a summary about the steps I've followed in order to
implement the features listed above.

retro-plugins:

 - Add pcsx_reARMed emulator to retro-plugins as the PlayStation plugin

gnome-games:

 - Split the result handling from the game creation
 - Add PlayStationPlugin to gnome-games
 - Add GameFactory interface and a generic implementation
 - Instead of using plain URIs, use Media wrapper class
 - Implement MediaSet class, allowing more than one URI per game
 - Implement the UI that allows the user changing media/discs in the middle of a game
 - Add PlayStationGameFactory for the PlayStation plugin


## Links

Links with the commits to each repository:

 - [retro-plugins](https://github.com/Kekun/retro-plugins/commits/master?author=zakum42)
 - [gnome-games](https://github.com/Kekun/gnome-games/commits/master?author=zakum42)


## Pictures

<figure>
  <a href="/img/posts/grand-turismo.png"><img src="/img/posts/grand-turismo.png" style="width: 400px; display: block;
  margin-left: auto;
  margin-right: auto;"/></a>
  <figcaption>PSX game in fullscreen, showing the multi-source menu on the right</figcaption>
</figure>

<br />

<figure>
  <a href="/img/posts/ff-anthology.png"><img src="/img/posts/ff-anthology.png" style="width: 400px; display: block;
  margin-left: auto;
  margin-right: auto;"/></a>
  <figcaption>Another PSX game, showing the multi-source menu</figcaption>
</figure>

<br />

In case of wanting to see the contribution live, please go to the gnome-games [repository](https://github.com/Kekun/gnome-games) to install the latest
version of the app.
