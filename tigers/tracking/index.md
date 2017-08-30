---
layout: tiger
title: Pack 818 - Claremont, CA
scouts:
  - name: Ar
    -bj1: X
  - Er
  - Ev
  - Ms
  - Mt
---

{% for scout in page.scouts %}
{{ scout.name }}
    
|Adventure | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|-------|--------|---------|---------|---------|---------|---------|---------|---------|
| Backyard Jungle | {{ scout.bj1 }} | | | | | | | |
| Games Tigers Play | | | | | | | | |
| Duty to God | | | | | | | | |
| Team Tiger | | | | | | | | |
| Tiger Bites | | | | | | | | |
| Tigers in the Wild | | | | | | | | |
| Tiger-iffic | | | | | | | | |
| Curiosity, Intrigue, <br>and Magical Mysteries | | | | | | | | |

{% endfor %}
