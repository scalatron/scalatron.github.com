---
layout: default
title: Scalatron
---

## The Scalatron Bot Benchmark

The highly official *Scalatron Bot Benchmark* lets you compare the performance of your bots to those of others.
It is somewhat artificial because it evaluates your bot in isolation, but at least it gives you a baseline.

To get your benchmark score, follow these steps:

* Remove all bots from the game, except for the one you want to evaluate; simply move them out of the `/Scalatron/bots/` directory.
* Start a game with 100×100 cells and 5000 steps per round. You can do this by changing into the `/Scalatron/bin/` directory
  and starting Scalatron from the command line via `java -server -jar Scalatron.jar -x 100 -y 100 -steps 5000`.
* Let the game run for at least 20 rounds. Tip: resize the window to a smaller size to speed up the simulation.
* Note down the “last 20″ average score of your bot that is displayed in the leader board (bottom right of the window).
* If you are of the hyper-competitive type, wait for as long as you want to get a satisfactory 20-round score.


## Official High Score

The highest verified score sent in by a user (rounded to the nearest hundred):

* Harvester Bot by @mj604 (April 17, 2012): 941,200


## Scores Of Example Bots

Here are some benchmark scores for the example bots included with Scalatron (rounded to the nearest hundred):

* Reference Bot: 17,400
* Passive Bot: -7,000
* Plant Approacher Bot: -7,700
* Brownian Motion Bot: -14,500

You can post your bots and their benchmark scores on the [Scalatron User Group](https://groups.google.com/d/forum/scalatron).

