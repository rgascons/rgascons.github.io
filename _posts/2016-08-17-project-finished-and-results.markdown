---
layout: post
title:  "GSoC: final week and results"
date:   2016-08-17 12:00:00 +02:00
categories: gsoc
---
Hello everyone, I'm very glad to announce that my GSoC project about implementing
games with multiple medias is being finished this very week. Although the code is still being tested, it won't have big changes. With that said, I'll show and explain the results.

My project is split into four major patches (although it's likely there will
be more than three commits):

 * Support PlayStation games through *retro-plugins*
 * Decouple the URI handling and game creation from *mime-type-tracker*
 * Abstracting game creating in *mime-type-tracker* into *game-uri-factory*
 * Support multi-source games

<br />
Here are a couple of pictures, showing the final results (open them for a bigger
  resolution):

<figure>
  <img src="/img/posts/ffviii-final.png" style="width: 400px; display: block;
  margin-left: auto;
  margin-right: auto;"/>
  <figcaption>PSX game in fullscreen, showing the multi-source menu on the right</figcaption>
</figure>

<br />

<figure>
  <img src="/img/posts/grand-turismo-final.png" style="width: 400px; display: block;
  margin-left: auto;
  margin-right: auto;"/>
  <figcaption>Another PSX game, showing the multi-source menu on the right</figcaption>
</figure>

<br />

I will post one final post with the final evaluation and more results. Stay tunned! :)
