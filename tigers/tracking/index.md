---
layout: tiger
title: Pack 818 - Claremont, CA
scouts:
  - name: Ar
    task:
    - bj1: X
    - bj2: X
  - name: Er
    task:
    - bj1: X
    - bj2: X
  - name: Ev
    task:
    - bj1: O
    - bj2: X
  - name: Ms
    task:
    - bj1: X
    - bj2: X
  - name: Mt
    task:
    - bj1: Y
    - bj2: X
---

{% for scout in page.scouts %}

{{ scout.name }}
    
|Adventure | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|-------|--------|---------|---------|---------|---------|---------|---------|---------|
| Backyard Jungle | {{ scout.task.bj1 }} | {{ scout.name }} | | | | | | |
| Games Tigers Play | | | | | | | | |
| Duty to God | | | | | | | | |
| Team Tiger | | | | | | | | |
| Tiger Bites | | | | | | | | |
| Tigers in the Wild | | | | | | | | |
| Tiger-iffic | | | | | | | | |
| Curiosity, Intrigue, <br>and Magical Mysteries | | | | | | | | |

{% endfor %}
