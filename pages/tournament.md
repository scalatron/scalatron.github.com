---
layout: default
title: Scalatron
---

## How To Run A Tournament or Workshop

There are two common reasons people get together with friends to run a Scalatron tournament:

* **A hack-a-thon** with programmers that already know Scala. You might do this as a team event at your company,
  as an event at a hackerspace or as a fun way to hack some code at a conference or user group meeting.
* **A training workshop** with programmers or students that don't yet know Scala but are open to try it;
  this is a great way to motivate people to learn: the focus is on a fun problem (writing a bot); Scala
  just happens to be the tool of choice.



### What You Need

To run a workshop, you need the following things:

* A **Server**: the spec depends on the number of players.
<ul>
    <li>For up to six players, we've had good experience with a 2009 Mac Mini, 1GB RAM, 2 cores.</li>
    <li>For larger groups (up to 20 players), you'll probably want beefier hardware and more RAM.</li>
    <li>In synthetic stress tests, Scalatron handled simultaneous 50 players on a 2007 Mac Pro, 4GB RAM, 8 cores.</li>
    <li>If you find that something works well (or not), please <a href="mailto:scalatron@hotmail.com">drop us a note</a>!</li>
</ul>
* **Players** (up to 20):
<ul>
    <li>Invite them ideally at least two weeks in advance.</li>
    <li>You may want to use a site like <a href="http://doodle.com">doodle.com</a> to pick a date.</li>
    <li>Send them a link to this site, or to <a href="http://scala-lang.org">the main scala site</a> if you don't want to give away the game.</li>
</ul>
* **Time**: how much depends on the format you want to use:
<ul>
    <li>For a "casual" workshop (browser-based): an evening (minimum 2 hours, ideally 4 hours)</li>
    <li>For a "serious" workshop (local builds): a day (minimum 4 hours, ideally 6-7 hours)</li>
    <li>For details on the different approaches, see the notes in the
      <a href="https://github.com/scalatron/scalatron/blob/master/Scalatron/doc/markdown/Scalatron%20Player%20Setup.md">player setup guide</a>.</li>
</ul>


### Preparation

Before people arrive, run through this checklist:

* **Server Works?** Download, install & run Scalatron. Verify that the tournament loop works and the game is
  visible in the main window.
* **Compile Service Works?** Create a user account, connect with a browser (from local machine is OK), load up an example bot
  (go into the tutorial index, select a sample, then click "Load into Editor" and hit "Run in Sandbox". If the bot
  shows up in the sandbox debugger, this works.
* **Network Works?** Create a user account, connect with a browser **from another machine** and verify that
  you can reach the Scalatron server's built-in web server (i.e. get to the welcome / log-in screen).
* **Documentation Available?** Make sure people can get to the tutorial and setup docs that you think they will
  need. If the Internet is not reachable (e.g. because of guest access restrictions at your company) make sure
  you put the key docs onto a USB stick in advance.
* **Food & Drinks**? No-one wants to be hungry or thirsty...

