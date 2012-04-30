---
layout: default
title: Scalatron
---

## How To Build

If you want to build Scalatron from scratch on your own computer,
[download the sources of the 'master' branch](http://github.com/scalatron/scalatron/zipball/master) and build them
with the [Simple Build Tool (SBT)](http://github.com/harrah/xsbt) for Scala.


## Install SBT

If you do not have SBT installed, check out the [online documentation](https://github.com/harrah/xsbt/blob/0.13/README.md)
and [setup guide](https://github.com/harrah/xsbt/wiki/Getting-Started-Setup) for SBT.


## Build Scalatron

Once you have SBT installed, open a terminal window and change into the directory into which you downloaded
(and unzipped) the Scalatron sources (the directory that contains this the `build.sbt` file) via e.g.

    cd /usr/dev/Scalatron

and run

    sbt dist

This will generate a new directory called `dist` which contains the same content as the regular distribution,
as well as a zip-file that contains exactly the content that represents the end-user distribution.


## Run Scalatron

To verify that everything worked, either install the resuting `.zip` file as you would with one your downloaded
as usual; or `cd` into the distribution directory `/dist/bin` and run `java -jar Scalatron.jar`:

    cd /usr/dev/Scalatron/dist/bin
    java -jar Scalatron.jar
