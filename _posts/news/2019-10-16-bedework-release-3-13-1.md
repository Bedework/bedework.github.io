---
layout: default
title:  "Bedework 3.13.1 Released"
menuTitle: ""
permalink: /news/bedework-3-13-1-released
---

*Posted <time>{{ page.date | date: "%B %-d, %Y" }}</time>*


<p>Bedework version 3.13.1 is now available. Installation instructions can be found  at <a href="http://bedework.github.io/bedework/#installing-the-quickstart">http://bedework.github.io/bedework/#installing-the-quickstart</a></p>

<p>Release notes are at <a href="http://bedework.github.io/bedework/#release-notes">http://bedework.github.io/bedework/#release-notes</a></p>

<p>This release has some performance improvements.
</p>
<ul>
<li>There was a long standing bug in category handling for updates. An attempt
    was made to preserve default categories for calsuites when an event is
    updated. For example if an event is suggested and accepted the
    accepting calsuite has its default category added to the event.This code was being applied to collections which made it impossible to turn off a default category added to, e.g. an alias, by mistake.</li>
<li>Many other smaller fixes.</li>
</ul>

