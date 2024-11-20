---
layout: home
title: Home Page
description: Home Page
nav_order: 1
nav_exclude: false
permalink: /:path/
seo:
  type: Course
  name: Home
---

# Welcome to the MUDE in Madras
{:.no_toc}

_View this page as a_ **Student**{: .label .label-green }

MUDE in Madras is a module at the Civil Engineering and Geosciences faculty of Delft University of Technology: {{ site.tagline }}, taken by all first year students in the MSc degree programs Applied Earth Sciences (AES), Environmental Engineering (EE) and Civil Engineering (CE).

### Most recent announcement

*A record of previous announcements can be found on the [All Announcements page]({{ site.baseurl }}/announcements).*

{% if site.announcements %}
{{ site.announcements.last }}
[Previous Announcements](announcements){: .btn .btn-outline .fs-3 }
{% endif %}


## Table of contents
{: .no_toc .text-delta }

1. TOC
{:toc}
