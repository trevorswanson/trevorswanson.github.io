---
title: "D&D"
layout: archive
permalink: /dnd/
excerpt: "As I get back into 5e, I'll start throwing notes and recaps onto my blog."
header:
  overlay_image: /assets/images/dnd-header.png
  overlay_filter: 0.5
feature_row:
  - image_path: /assets/images/icespire-peak.jpg
    alt: "Dragon of Icespire Peak"
    title: "Dragon of Icespire Peak Coming Soon"
    excerpt: "<i>(Coming Soon)</i><br />Introducing two of my friends to D&D with the help of two more experienced players"
---
## Latest Posts
    {% for post in site.categories.d-d limit:5 %}
           {% include archive-single.html type=entries_layout %}
    {% endfor %}

## Campaigns

{% include feature_row %}

## Helpful Resources

### DMs
* [Treasure Generator](http://redkatart.com/dnd5tools/)
* [donjon](http://donjon.bin.sh/5e/)
* [Kobold Fight Club](http://kobold.club/fight/)

### Players
