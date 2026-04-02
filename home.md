---
layout: home
title: Home / Calendar
description: Listing of course modules and topics.
permalink: /:path/
nav_order: 0
seo:
  type: Course
  name: Just the Class
---

{: .warning }
⚠️ This content is archived as of March 2026 and is retained exclusively for reference. [Find current offerings.](https://data88e.org/)

# Data 88E: Economic Models

{: .mb-2 }
UC Berkeley, Fall 2024
{: .mb-0 .fs-6 .text-grey-dk-000 }

{% assign instructors = site.staffers | where: 'role', 'Instructor' %}
{% for staffer in instructors %}
{{ staffer }}
{% endfor %}

{% for module in site.modules %}
{{ module }}
{% endfor %}
