---
layout: default
title:  "Bedework 4.1.0 Released"
menuTitle: ""
permalink: /news/bedework-4-1.0-released
---

*Posted <time>{{ page.date | date: "%B %-d, %Y" }}</time>*


<p>Bedework version 4.1.0 is now available. Installation instructions can be found  at <a href="https://bedework.github.io/bedework/#featurepack-install">https://bedework.github.io/bedework/#featurepack-install</a></p>

<p>Release notes are at <a href="http://bedework.github.io/bedework/#release-notes">http://bedework.github.io/bedework/#release-notes</a></p>

<p>This release has, once again, been a long time coming. Again there have been many internal changes. The bw-xml project most other projects depended on has gone. Struts 1 has been replaced with struts 2 - mostly to avoid the toxic dependencies. 
</p>
<p>
As always there are a bunch of bug fixes, many in handling of recurring events.
</p>
<p>
We are now running on jdk 17 and wildfly 26. This has resulted in performance improvements. I would see intermittent crashes on the earlier wildfly - these have now stopped. Additionally, memory management has improved significantly. 
</p>
