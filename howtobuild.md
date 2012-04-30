---
layout: default
title: Scalatron - How To Build
---


If you want to get the source code and build Scalatron yourself,
[download the sources of the 'master' branch](http://github.com/scalatron/scalatron/zipball/master and build them
with [SBT](http://github.com/harrah/xsbt). Once you have SBT installed, switch to the directory where you downloaded
the Scalatron sources (the directory that contains this the `build.sbt` file) and run

    sbt dist

This will generate a new directory called `dist` which contains the same content as the regular distribution.
Now `cd` into `/dist/bin` and run `java -jar Scalatron.jar`.
