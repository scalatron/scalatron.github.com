---
layout: default
title: Scalatron
---

## The Scalatron Benchmark

The highly official *Scalatron Bot Benchmark* lets you compare the performance of your bots to those of others.
It is somewhat artificial because it evaluates your bot in isolation, but at least it gives you a baseline.

To get your benchmark score, follow these steps:

* Remove all bots from the game, except for the one you want to evaluate; simply move them out of the `/Scalatron/bots/` directory.
* Start a game with 100×100 cells and 5000 steps per round. You can do this by changing into the `/Scalatron/bin/` directory
  and starting Scalatron from the command line via `java -server -jar Scalatron.jar -x 100 -y 100 -steps 5000`.
* Let the game run for at least 20 rounds.
* Note down the “last 20″ average score of your bot that is displayed in the leader board (bottom right of the window).
* If you are of the hyper-competitive type, wait for as long as you want to get a satisfactory 20-round score.

**Tips**:

* To accelerate the simulation, resize the window to a small size.
* To allow maximum CPU allocation to the simulation, use the command line option `-maxfps 1000`.
* You can also try the Scalatron [command line tool's](https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20CLI.md) `benchmark` command.

## Official High Score

The highest *verified* scores sent in by users (rounded to the nearest hundred):

* **[PandaCub](https://bitbucket.org/asflierl/pandacub/wiki/Home)** by [@asflierl](http://twitter.com/asflierl) (May 4, 2012): 2,760,800
* **Harvester Bot** by @mj604 (April 17, 2012): 941,200


## Scores Of Example Bots

Here are some benchmark scores for the example bots included with Scalatron (rounded to the nearest hundred):

* Reference Bot: 17,400
* Passive Bot: -7,000
* Plant Approacher Bot: -7,700
* Brownian Motion Bot: -14,500

You can post your bots and their benchmark scores on the [Scalatron User Group](https://groups.google.com/d/forum/scalatron).

