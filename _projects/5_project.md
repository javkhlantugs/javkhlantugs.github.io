---
layout: page
title: Crossword
description: given a number of words, solve a crossword puzzle using backtracking algorithm
img: assets/img/output.png
importance: 5
category: personal
---

<div class="row">
<div class="col">
    <a class="btn btn-outline-light" href="https://github.com/javkhlantugs/crossword">Code</a>
    </div>
</div>

# About

Given the structure of a crossword puzzle (i.e., which squares of the grid are meant to be filled in with a letter), and a list of words to use, the problem becomes one of choosing which words should go in each vertical or horizontal sequence of squares. I have modeled this sort of problem as a constraint satisfaction problem. Each sequence of squares is one variable, for which we need to decide on its value (which word in the domain of possible words will fill in that sequence).

# Example

{% include figure.html path="assets/img/output.png" title="example image" class="img-fluid rounded z-depth-1" %}
