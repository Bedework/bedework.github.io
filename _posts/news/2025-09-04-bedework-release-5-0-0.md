---
layout: default
title:  "Bedework 5.0.0 Released"
menuTitle: ""
permalink: /news/bedework-5-0-0-released
---

*Posted <time>{{ page.date | date: "%B %-d, %Y" }}</time>*

<p>Bedework version 5.0.0 is now available. Installation instructions can be found  at <a href="https://bedework.github.io/bedework/#featurepack-install">https://bedework.github.io/bedework/#featurepack-install</a></p>

<p>Release notes are at <a href="http://bedework.github.io/bedework/#release-notes">http://bedework.github.io/bedework/#release-notes</a></p>

<p>This release took a long time. We had various obstacles to overcome.

1. The javax to jakarta migration required many updates and the presence of migrated dependencies. 
2. Many dependencies decided it was a good time to make incompatible changes. Moving to the jakarta release involved substantial changes for struts and hibernate along with many smaller changes.
3. Sonatype migration. This happened at the same time and required changes to the build and release process.
</p>
<p>
Changes have been made to project structures to try to increase the openssf scorecard ranking. Partly prompted by sonatype no longer doing dependency checking on release.
</p>
<p>
Each project will have its own changelog and has a dependency report available via github pages. This is currently a work in progress. 
</p>
<p>
As always there are a bunch of bug fixes, many in handling of recurring events (again).
</p>
<p>
We are now requiring jdk 21 and running on wildfly 35.
</p>
