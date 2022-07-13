---
title: "D&D"
layout: splash
permalink: /dnd/
excerpt: "As I get back into 5e, I'll start throwing notes and recaps onto my blog."
header:
  overlay_image: /assets/images/dnd-header.png
  overlay_filter: 0.2
feature_row:
  - image_path: /assets/images/rotf.jpeg
    alt: "Rime of the Frostmaiden"
    title: "Rime of the Frostmaiden"
    url: "dnd/rime-of-the-frostmaiden"
    excerpt: "Chronicling our (mis)adventures as I modify and run the wintry horror adventure for my friends."
    btn_label: "Read More"
    btn_class: "btn--inverse"
---

{% include feature_row %}

## Latest Posts
    {% for post in site.categories.dnd limit:5 %}
           {% include archive-single.html type=entries_layout %}
    {% endfor %}

## Helpful Resources

### DMs
* [Treasure Generator](http://redkatart.com/dnd5tools/)
* [donjon](http://donjon.bin.sh/5e/)
* [Kobold+ Fight Club](https://koboldplus.club/)
* [Kassoon D&D Generators](https://www.kassoon.com/dnd/dnd)
* [Fantasy Calendar](https://fantasy-calendar.com/)

### Players
