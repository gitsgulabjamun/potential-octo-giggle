---
layout: template_demo
author: Robert Louis Stevenson
---

# Home page

Who am I?

My name is {{ page.author }}.

This was done as {{ site.what }} in the {{ site.when }}.

My name is Caran D’Arche. I am a pencil, and I was born in Geneva. A few days after my birth, my family moved to Bangalore, where I went to school and college. I graduated top of my class from the Faber-Castell Architecture University, and interned as draughtsperson at Kohinoor Hardtmuth.

What do I do?

My professional areas of interest include drawing, sketching, and designing. I specialise in drawing space-rovers and drone-probes.
At my current company, I was instrumental in implementing a Sharp-and-Clear-Lines policy that reduced smudges by 43% and raised designer satisfaction by more than 78 basis points.

Here’s my employment history:

    {% for item in site.data.employment %}
    {{ item.years }}, {{ item.company }}
    {% endfor %}

What am I looking for?

I am looking for a role where I can use my special point-and-mark skills to annotate research papers at academic institutions that offer certificate courses in the following areas: mythology, war games, and kite making.
