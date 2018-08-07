---
layout: page
title: Puzzles
types:
- number
- visual
- geometry
- dudeney
---
* 
{:toc}

# Puzzles
{% for type in page.types %}
## {{ type | capitalize }} Puzzles
{% if type == 'dudeney' %}
A selection of some of the more satisfying puzzles drawn from Henry Ernest Dudeney's "[The Canterbury Puzzles](http://www.gutenberg.org/ebooks/27635)" and "[Amusements in Mathematics](http://www.gutenberg.org/ebooks/16713)".
{% endif %}
    {% for puzzle in site.puzzles %}
        {% if puzzle.category == type %}
### {{ puzzle.title }}
*~ {% if puzzle.tweet %}[{{ puzzle.date | date: "%d %B %Y"}}]({{ puzzle.tweet }}){% else %}{{ puzzle.date | date: "%d %B %Y"}}{% endif %}* {% if puzzle.source %}([Source]({{ puzzle.source }})) {% endif %}
{{ puzzle.content }}
            {% if puzzle.image %}
![{{ puzzle.title }} image]({{ site.img }}/puzzles/{{ puzzle.image }})
            {% endif %}
            {% if puzzle.solutions %}
[Solutions](#{{ puzzle.title | slugify }}-solution) 
            {% endif %}
        {% endif %}
    {% endfor %}
{% endfor %}
<hr>
# Solutions
{% for type in page.types %}
## {{ type | capitalize }} Puzzles
    {% for sol in site.solutions %}
        {% if sol.category == type %}
### {{ sol.title }} Solution
{{ sol.content }}
        {% endif %}
    {% endfor %}
{% endfor %}