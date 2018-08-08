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




















# Unsorted
## Big Puzzles
### Shikaku

[Link](https://twitter.com/nomad_penguin/status/1011178869208969216)


## Games
### Exploring Spot-It

[Link](https://twitter.com/DavidKButlerUoA/status/1022600097421381632)

[Link](https://twitter.com/DavidKButlerUoA/status/986479655560527872)


### Exploring SET

[Link](https://twitter.com/DavidKButlerUoA/status/1016938264337440769)


### Exploring Prime Climb

[Link](https://twitter.com/DavidKButlerUoA/status/1016886479627272193)

### Jenga Views
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Ok, I&#39;ve remade <a href="https://twitter.com/JDHamkins?ref_src=twsrc%5Etfw">@JDHamkins</a>&#39;s Ortho-Projections activity (<a href="https://t.co/6zyitDTAj6">https://t.co/6zyitDTAj6</a>) so it uses Jenga blocks. I&#39;m excited to try it at <a href="https://twitter.com/hashtag/100factorial?src=hash&amp;ref_src=twsrc%5Etfw">#100factorial</a> today! <a href="https://t.co/mS7dIW7lMZ">pic.twitter.com/mS7dIW7lMZ</a></p>&mdash; David Butler (@DavidKButlerUoA) <a href="https://twitter.com/DavidKButlerUoA/status/1001615635376324608?ref_src=twsrc%5Etfw">May 30, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Link](https://twitter.com/DavidKButlerUoA/status/1001616709051035649)


### Card-io tiles
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">At <a href="https://twitter.com/hashtag/100factorial?src=hash&amp;ref_src=twsrc%5Etfw">#100factorial</a> playing with <a href="https://twitter.com/panlepan?ref_src=twsrc%5Etfw">@panlepan</a>’s Card-io tiles. We’re trying to see if we can arrange them in the 7by10 grid with all two-coloured hearts. <a href="https://t.co/0bSvLUZ314">pic.twitter.com/0bSvLUZ314</a></p>&mdash; David Butler (@DavidKButlerUoA) <a href="https://twitter.com/DavidKButlerUoA/status/991532710953762816?ref_src=twsrc%5Etfw">May 2, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Link](https://twitter.com/panlepan/status/991432222522691584)

### Loop cards
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">This from <a href="https://twitter.com/panlepan?ref_src=twsrc%5Etfw">@panlepan</a> looks like something cool to do at <a href="https://twitter.com/hashtag/100factorial?src=hash&amp;ref_src=twsrc%5Etfw">#100factorial</a> this Wednesday! <a href="https://t.co/qi9Mjy0Rjd">https://t.co/qi9Mjy0Rjd</a></p>&mdash; David Butler (@DavidKButlerUoA) <a href="https://twitter.com/DavidKButlerUoA/status/990718485247356928?ref_src=twsrc%5Etfw">April 29, 2018</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Link](https://twitter.com/DavidKButlerUoA/status/990718485247356928)

## Other (Unsorted)


































### Which Number Where

[Link](https://twitter.com/DavidKButlerUoA/status/968669417851662337)

### Amidakuji

[Link](https://twitter.com/DavidKButlerUoA/status/963592247387107328)


### Five Triangles

[Link](https://twitter.com/Five_Triangles/media)

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



### Shaded fraction

[Link](https://twitter.com/DavidKButlerUoA/status/797517127921958912)

### Open Middle problem

[Link](https://twitter.com/DavidKButlerUoA/status/797186971437146112)

[Link](https://twitter.com/DavidKButlerUoA/status/780665180292210688)

[Link](https://twitter.com/MrJohnRowe/status/767867474322731008)

### 

[Link](https://twitter.com/DavidKButlerUoA/status/796122484634361856)

### Sprouts

[Link](https://twitter.com/DavidKButlerUoA/status/780984356726796288)

### Fraction Skyscraper

[Link](https://twitter.com/DavidKButlerUoA/status/780983234209390592)





### Mathematical Card Magic

[Link](https://twitter.com/DavidKButlerUoA/status/771076359913213952)


### 
<blockquote class="twitter-tweet" data-lang="en"><p lang="en" dir="ltr">Interesting thing to investigate for <a href="https://twitter.com/hashtag/100factorial?src=hash&amp;ref_src=twsrc%5Etfw">#100factorial</a> soon <a href="https://t.co/IrKg7C3ZAn">https://t.co/IrKg7C3ZAn</a></p>&mdash; David Butler (@DavidKButlerUoA) <a href="https://twitter.com/DavidKButlerUoA/status/768080817104957440?ref_src=twsrc%5Etfw">August 23, 2016</a></blockquote>
<script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>

[Link](https://twitter.com/DavidKButlerUoA/status/768080817104957440)




7 June 2016