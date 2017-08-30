---
layout: tiger
title: Pack 818 - Claremont, CA

scouts:

  - name: Ar
    bjung: 
    - t1: X
    - t2: X
    - t3: -
    
  - name: Er
    bj1: X
    bj2: X
    
  - name: Ev
    bj1: X
    bj2: X
    
  - name: Ms
    bj1: X
    bj2: X
    
  - name: Mt
    bj1: X
    bj2: X
    
---

{% for scout in page.scouts %}

{{ scout.name }}
    
|Adventure | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 |
|-------|--------|---------|---------|---------|---------|---------|---------|---------|
| Backyard Jungle | {% for task in scout.bjung %} {{ task }} | {% endfor %}
| Games Tigers Play | | | | | | | | |
| Duty to God | | | | | | | | |
| Team Tiger | | | | | | | | |
| Tiger Bites | | | | | | | | |
| Tigers in the Wild | | | | | | | | |
| Tiger-iffic | | | | | | | | |
| Curiosity, Intrigue, <br>and Magical Mysteries | | | | | | | | |

{% endfor %}
