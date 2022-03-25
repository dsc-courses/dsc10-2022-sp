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

<b style='color: red'>Update as of January 31st:</b>
- Lectures, discussions, and some office hours are now offered in-person. **Lectures are in Center Hall 214, and discussions are in Center Hall 105.** You may still join all lectures and discussions remotely via Zoom by using the link below.
- In addition to watching recordings by clicking the 🎥 buttons below, you can watch in-person recordings on [podcast.ucsd.edu](https://podcast.ucsd.edu) if you'd prefer.
- Some office hours are in-person and some are remote; see the [Calendar](../calendar) for more details.


[Zoom Link](https://ucsd.zoom.us/j/96971704832){: .btn .btn-blue } [Recordings](https://www.youtube.com/playlist?list=PLDNbnocpJUhZDpPKmmbgXAuZqYYPhC0D-){: .btn .btn-green }

{% for module in site.modules %}
{{ module }}
{% endfor %}
