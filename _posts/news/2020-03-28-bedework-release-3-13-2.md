---
layout: default
title:  "Bedework 3.13.2 Released"
menuTitle: ""
permalink: /news/bedework-3-13-2-released
---

*Posted <time>{{ page.date | date: "%B %-d, %Y" }}</time>*


<p>Bedework version 3.13.2 is now available. Installation instructions can be found  at <a href="http://bedework.github.io/bedework/#installing-the-quickstart">http://bedework.github.io/bedework/#installing-the-quickstart</a></p>

<p>Release notes are at <a href="http://bedework.github.io/bedework/#release-notes">http://bedework.github.io/bedework/#release-notes</a></p>

<p>This release has some performance improvements.
</p>
<ul>
<li>Dropped a wait in indexing mark-transaction which was adding a significant amount of time to calls.</li>
<li>Figured out how to handle provisioning a new account when we have a read-only svci. Allowed reinstating read-only for caldav read-only methods.</li>
</ul>
