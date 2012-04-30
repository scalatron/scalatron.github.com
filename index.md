---
layout: default
title: Scalatron
---

Scalatron is a multi-player programming game in which bot programs written in [Scala](http://www.scala-lang.org/)
compete against each other. It is an educational resource for individuals or teams that want to learn more about the
Scala programming language or want to hone their Scala programming skills.

Follow [@scalatron on Twitter](http://twitter.com/scalatron).

**April 30, 2012: Work in Progress**

## You Want To Learn Scala?

Install Scalatron and work through the detailed, step-by-step tutorial for writing bots in Scala. It assumes no
prior knowledge of the language.

<table>

<tr>
<td>
**Getting Started**

[Download the Scalatron game](http://github.com/scalatron/scalatron/downloads) and unzip it. Go into the `/bin` directory and run `Scalatron.jar`.
</td>
<td>
**The Botwar Game**

Compete for energy units in a cell-based arena with edible and harmful plants and beasts. For details, see the [Game Rules](https://github.com/scalatron/scalatron/raw/master/Scalatron/doc/pdf/Scalatron%20Game%20Rules.pdf).
</td>
</tr>

<tr>
<td>
**Scala Tutorial**

A [step-by-step tutorial](https://github.com/scalatron/scalatron/raw/master/Scalatron/doc/pdf/Scalatron%20Tutorial.pdf) teaches you Scala and helps you build your first bot.
</td>
<td>
...
</td>
</tr>

<tr>
<td>
**The Scalatron Protocol**

Read the [Protocol](https://github.com/scalatron/scalatron/raw/master/Scalatron/doc/pdf/Scalatron%20Protocol.pdf) spec to understand exactly how the game and your bot interact.
</td>
<td>
**High Scores**

You can use the [Scalatron Benchmark](benchmark.html) to rate your bot and compare it to others' in the [high score list](benchmark.html).
</td>
</tr>

</table>



## You Want To Organize a Tournament?

The basic idea is that a fun, competitive environment and a self-paced tutorial (pdf) that provides quick results is a great way to quickly become productive in a new language.


## You Want To Make Scalatron Better?



## How to Run

If you want to run Scalatron to play the game or to run a workshop with friends, simply
[download the latest version](http://github.com/scalatron/scalatron/downloads) - you do not need the
source code. Unzip the downloaded file into a local directory, then look for the `Readme.txt` file to get
started. Have fun!

## How to Build

If you want to get the source code and build Scalatron yourself,
[download the sources of the 'master' branch](http://github.com/scalatron/scalatron/zipball/master and build them
with [SBT](http://github.com/harrah/xsbt). Once you have SBT installed, switch to the directory where you downloaded
the Scalatron sources (the directory that contains this the `build.sbt` file) and run

    sbt dist

This will generate a new directory called `dist` which contains the same content as the regular distribution.
Now `cd` into `/dist/bin` and run `java -jar Scalatron.jar`.


## Contributing

[Fork Scalatron here on github](http://github.com/scalatron/scalatron/fork and send pull requests.
Bring your own ideas or check out the [list of open issues](http://github.com/scalatron/scalatron/issues?state=open),
many of which contain relatively detailed pointers on how/where to get started implementing something.
Before embarking on something major, you can [contact the maintainer](mailto:scalatron@hotmail.com) and ask for
feedback or tips on where to get started.


## License

Scalatron is licensed under the [Creative Commons Attribution 3.0 Unported License](http://creativecommons.org/licenses/by/3.0/).
The documentation, tutorial and source code are intended as a community resource and you can basically use, copy and
improve them however you want. Included works are subject to their respective licenses.