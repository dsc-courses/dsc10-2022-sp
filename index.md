---
layout: home
title: Home
nav_exclude: false
nav_order: 1
---

# {{ site.tagline }} 📊
{: .mb-2 }
{{ site.description }}
{: .fs-6 .fw-300 }

{{ site.staffersnobio }}

<b style='color: red'>Disclaimer:</b>
- This website is a work in progress and nothing you see here is accurate until this disclaimer is removed.

[Zoom Link for Remote Office Hours](https://ucsd.zoom.us/j/96971704832){: .btn .btn-blue } [Podcasts](https://podcast.ucsd.edu/default.aspx){: .btn .btn-green }

{% for module in site.modules %}
{{ module }}
{% endfor %}
