---
layout: page
title: "#100factorial"
permalink: /100factorial/
types:
- number
- visual
- geometry
- dudeney
- game
---
# About
{:.no_toc}

David Butler ([@DavidKButlerUoA](https://twitter.com/DavidKButlerUoA)) of the Maths Learning Centre at the University of Adelaide runs a puzzle and games club called "One Hundred Factorial" (named after the first puzzle the club tackled - read more [here](https://www.adelaide.edu.au/mathslearning/play/)). 

Across the years, many of these puzzles have been shared through photos on Twitter using [#100factorial](https://twitter.com/search?q=%23100factorial). Here I aim to currate a list of all the puzzles that have been shared, with descriptions and possible solutions, eventually with some degree of organisation, to aid in finding puzzles quicklky in the future.

Other sources of puzzles:
- [The NRICH Project](https://nrich.maths.org/) (University of Cambridge)
- [Double Helix](https://twitter.com/CSIROhelix) (CSIRO)
- [Canadian Math Kangaroo Contest](https://kangaroo.math.ca)
- [Brilliant.org](https://brilliant.org/)
- [Open Middle](http://www.openmiddle.com/)
- [@Five_Triangles](https://twitter.com/Five_Triangles)
- [@jamestanton](https://twitter.com/jamestanton)

# Contents
{:.no_toc}
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
            {% if puzzle.file %} 
                {% if puzzle.file contains 'jpg' or 'png' %}
![{{ puzzle.title }} image]({{ site.img }}/puzzles/{{ puzzle.file }})
                    {% else %}
                    [File]({{ site.img }}/puzzles/{{ puzzle.file }})
                {% endif %}
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























# Unsorted


### Amidakuji

[Link](https://twitter.com/DavidKButlerUoA/status/963592247387107328)


### 2018

[Link](https://twitter.com/DavidKButlerUoA/status/953365281807548416)



### Exploding Dots

[Link]()



### Competative Four-colouring
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Competitive four-colouring at <a href="https://twitter.com/hashtag/100factorial?src=hash&amp;ref_src=twsrc%5Etfw">#100factorial</a>. Two teams. Colour a region so that same colours don&#39;t touch by edge. Last valid move wins. <a href="https://t.co/F1j0piDuI9">pic.twitter.com/F1j0piDuI9</a></p>&mdash; David Butler (@DavidKButlerUoA) <a href="https://twitter.com/DavidKButlerUoA/status/910312037753827329?ref_src=twsrc%5Etfw">September 20, 2017</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Link](https://twitter.com/DavidKButlerUoA/status/910312037753827329)








### Circles in a triangle

[Link](https://twitter.com/nomad_penguin/status/861921504409272324)


### Card walk

[Link](https://twitter.com/DavidKButlerUoA/status/862162488384737281)


### Polydivisible number

[Link](https://en.wikipedia.org/wiki/Polydivisible_number)




### ???

[Link](https://twitter.com/DavidKButlerUoA/status/836796477376770049)

### Sums of squares

[Link](http://www.squeaktime.com/blog/sums-of-squares-squared)

### 

[Link](https://mhorley.wordpress.com/2017/02/24/algebra/)

### Buckets of fish!

[Link](http://jdh.hamkins.org/buckets-of-fish/)

### 

[Link](https://twitter.com/DavidKButlerUoA/status/829030905985396736)

### Domino Grids

[Link](https://twitter.com/DavidKButlerUoA/status/829029165793882112)

### The Crossword that counts itself

[Link](https://twitter.com/nomad_penguin/status/820570486887174144)

### Akari

[Link](https://twitter.com/nomad_penguin/status/817620108658884609)

### 

[Link](https://twitter.com/CmonMattTHINK/status/799673924149645312)


### Open Middle problem

[Link](https://twitter.com/DavidKButlerUoA/status/797186971437146112)

[Link](https://twitter.com/DavidKButlerUoA/status/780665180292210688)

[Link](https://twitter.com/MrJohnRowe/status/767867474322731008)

### James Tanton

[Link](https://twitter.com/DavidKButlerUoA/status/796122484634361856)


### Fraction Skyscraper

[Link](https://twitter.com/DavidKButlerUoA/status/780983234209390592)





### Mathematical Card Magic

[Link](https://twitter.com/DavidKButlerUoA/status/771076359913213952)


### 
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Interesting thing to investigate for <a href="https://twitter.com/hashtag/100factorial?src=hash&amp;ref_src=twsrc%5Etfw">#100factorial</a> soon <a href="https://t.co/IrKg7C3ZAn">https://t.co/IrKg7C3ZAn</a></p>&mdash; David Butler (@DavidKButlerUoA) <a href="https://twitter.com/DavidKButlerUoA/status/768080817104957440?ref_src=twsrc%5Etfw">August 23, 2016</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Link](https://twitter.com/DavidKButlerUoA/status/768080817104957440)




7 June 2016