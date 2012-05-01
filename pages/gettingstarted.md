---
layout: default
title: Scalatron
---

## Get Started With Scalatron

Scalatron consists of these main parts:

* A **server application** that simulates the virtual game world in which players' bots compete. Besides running
  the tournament loop, this server also includes a web server to which players can connect to edit, build and test
  their bots in a browser. The entire source code of the server is available for you to
  <a href="https://github.com/scalatron/scalatron">browse</a> and
  <a href="https://github.com/scalatron/scalatron/zipball/master">download</a>.
* The **bot plug-ins** of the players, each of which contains compiled Scala code that determines the behavior
  of a particular player's bot. Example bots are included in the installation and their source code is also
  <a href="https://github.com/scalatron/scalatron/tree/master/Scalatron/samples">available online</a>.
* Extensive **documentation** on
  <a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Server%20Setup.md">how to set up the server</a>;
  <a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Player%20Setup.md">how to set up the players</a>;
  <a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Game%20Rules.md">what the game rules are</a>;
  <a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Protocol.md">how the server talks to bots</a>;
  and lastly a longish <a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Tutorial.md">step-by-step tutorial</a> on how to build a bot in Scala.


### How To Install

For details, check out the
<a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Server%20Setup.md">Scalatron Server Setup guide</a>
(also as <a href="http://github.com/scalatron/scalatron/raw/master/Scalatron/doc/pdf/Scalatron%20Server%20Setup.pdf">pdf</a>).
But here is an abbreviated version:

* [Download the latest version](https://github.com/scalatron/scalatron/downloads) of the Scalatron game as a .zip file from github
* Unzip the compressed file on your computer



### How To Run

Scalatron is a Scala application that is distributed as a compressed Java archive (.jar) file.
The file is called `Scalatron.jar` and you can find it in the `/bin` sub-directory inside the installation directory.
It can be started in two ways:

* By double-clicking the application file `Scalatron.jar`
* By opening a terminal, changing into the `/bin` directory and running `java -jar Scalatron.jar`

Note that in order to run Scalatron, you need to have the
<a href="http://www.java.com/download/">Java Runtime Environment</a> installed.


### What You Should See

Once you have the Scalatron server running, you should see two windows come up:

* The Scalatron **tournament window** showing a game in action, with a score board and leader board.
  If you are running a workshop with other players, you could use a projector to display this on a wall.
* A **web browser** showing a "Welcome To Scalatron" log-in screen; this is the entry page of the browser-based
  administration tools and of the Scalatron IDE (Integrated Development Environment). The IDE lets players edit,
  build, test and publish your bots without installing anything else.


### How To Play

To play, you can now write a bot program in Scala, build it, and publish it into the game.
There are two basic approaches to doing this, which are explained in laborious detail in the
<a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Player%20Setup.md">player setup guide</a>
(also as <a href="https://github.com/scalatron/scalatron/raw/master/Scalatron/doc/pdf/Scalatron%20Player%20Setup.pdf">pdf</a>):

* The **"serious" path** involves setting up a local development environment like IDEA, Eclipse or SBT.
  This approach is fairly complex and is recommended only for experienced programmers that wish to have full
  control over their development process. For details on how to do this, please refer to the *player setup guide* linked above.
* The **"casual" path** involves using the browser-based Scalatron IDE, which is a snap.

Here are the steps for getting started with the "casual", browser-based approach:

* If you do not have a browser window open already that is connected to the Scalatron server, open a web browser
  now and point it to the appropriate web address:
  <ul>
    <li>If you are on the same computer, try `http://localhost:8080`</li>
    <li>If you are on another computer, try the address the server tells you about on the console, such as `http://192.168.0.1:8080`</li>
  </ul>

* This should bring up the Scalatron log-in screen with the title "Welcome To Scalatron"
* Log in as `Administrator` (there is no password, initially)
* Create a user account for yourself and anyone else who wants to play
* Return to the welcome screen again
* Log in under the user account which you created for yourself
* This will take you into a browser-based code editor, pre-populated with the source code for a simple working bot
* Click **Run in Sandbox** to build your bot and run it in a private sandbox game
* Click **Publish into Tournament** to build your bot and publish it into the tournament


### What Next?

* Read the contents of the `Readme.txt` file in your installation directory (or <a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/Readme.txt">online</a>)
* All of the documentation is also available in the installation directory, in a sub-directory called `/doc` (or <a href="https://github.com/scalatron/scalatron/tree/master/Scalatron/doc">online</a>)
* Once you know your way around, invite some friends for a <a href="/pages/tournament.html">bot coding tournament</a> and have fun!
* [Fork Scalatron on github](https://github.com/scalatron/scalatron) and help us make it better!

