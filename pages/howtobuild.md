---
layout: default
title: Scalatron
---

## How To Build

If you want to build Scalatron from scratch on your own computer,
[download the sources of the 'master' branch](http://github.com/scalatron/scalatron/zipball/master) and build them
with the [Simple Build Tool (SBT)](http://github.com/harrah/xsbt) for Scala.


### Install SBT

If you do not have SBT installed, check out the [online documentation](https://github.com/harrah/xsbt/blob/0.13/README.md)
and [setup guide](https://github.com/harrah/xsbt/wiki/Getting-Started-Setup) for SBT.


### Build Scalatron

Once you have SBT installed, open a terminal window and change into the directory into which you downloaded
(and unzipped) the Scalatron sources (the directory that contains this the `build.sbt` file) via e.g.

    cd /usr/dev/Scalatron

and run

    sbt dist

This will generate a new directory called `dist` which contains the same content as the regular distribution,
as well as a zip-file that contains exactly the content that represents the end-user distribution.
Thanks to <a href="http://twitter.com/charleso">@charleso</a> for preparing Scalatron for SBT!


### Run Scalatron

To verify that everything worked, either install the resulting `.zip` file as you would with one you downloaded
as usual; or `cd` into the distribution directory `/dist/bin` and run `java -jar Scalatron.jar`:

    cd /usr/dev/Scalatron/dist/bin
    java -jar Scalatron.jar


### Now Contribute!

Once you got Scalatron to compile on your local machine, it's only a small step towards helping us
make it better: [fork us on github](https://github.com/scalatron/scalatron), make some improvements
and send a pull request!

Not sure where to start? Check out the [list of open issues](http://github.com/scalatron/scalatron/issues?state=open)
on Github. Many enhancement suggestions contain pointers to the files that need to be changed to get started.

Still not sure, or want confirmation? [Contact the maintainer](mailto:scalatron@hotmail.com) and ask for feedback,
ideas or tips.


