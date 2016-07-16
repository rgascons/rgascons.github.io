---
layout: post
title:  "Advancements in Gnome Games: multi-disk support"
date:   2016-07-06 12:00:00 +02:00
categories: gsoc
---
Hello my dearest followers :)

Exciting week progressing through my GSoC Proposal, programming and discussing
software design with my mentor. The main point of discussion in the recent days
has been over the fact that Gnome-Games is not well thought for games with multiple
disks. These is reflected in the SparQL queries and how a single URI means a single game.

On top of that, we have to inspect the file's meta-data to extract meaningful information
such as if the game is a proper PSsX game or what disc is it.

Right now, the discs' grouping is done in Gnome-Games. What's left is a tracker miner
for PSX files, to extract better information about the games.

Next post I'll be explaining in further detail how the tracker miner works
and what we do with it.
