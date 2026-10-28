---
layout: default
---

## Latest Transmission

{% for post in site.posts limit:1 %}

{% capture title %}{% include transmission-title.html post=post %}{% endcapture %}
### [{{ title | strip }}]({{ post.url }})
{:alt="{{ title | strip }}"}

<div class="preview">
{{ post.content }}
</div>

[Read more →]({{ post.url }})

{% endfor %}

## Sabacc Nights

### Coming Soon
{:alt="Coming Soon"}

More often than annual. We promise. Join us at Launch Pad in Aurora on select nights!

![Beer with the Launch Pad logo, with credits and a DL-44 blaster in the background](images/launchpad.jpg)

Email [cantina@blaede.family](mailto:cantina@blaede.family?subject=Sabacc) for more info.
