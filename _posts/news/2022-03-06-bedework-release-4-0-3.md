---
layout: default
title:  "Bedework 4.0.3 Released"
menuTitle: ""
permalink: /news/bedework-4-0-3-released
---

*Posted <time>{{ page.date | date: "%B %-d, %Y" }}</time>*


<p>Bedework version 4.0.3 is now available. Installation instructions can be found  at <a href="https://bedework.github.io/bedework/#featurepack-install">https://bedework.github.io/bedework/#featurepack-install</a></p>

<p>Release notes are at <a href="http://bedework.github.io/bedework/#release-notes">http://bedework.github.io/bedework/#release-notes</a></p>

<p>This release has been a long time coming largely because it involved a significant amount of restructuring. We've moved away from ElasticSearch because of licence issues, and completely overhauled the deployment process.
</p>
<p>
Part of the refactoring is to split off the read-only system from the read-write components. This would allow deployment of a much lighter weight service for feeds and web-presence. This work is not yet complete.
</p>
<p>
The bulk of the rest of the work is to use jboss modules to deploy all code once only and have that available for all services. This reduces memory usage and startup time.
</p>
