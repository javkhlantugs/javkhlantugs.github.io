---
layout: page
title: Parser
description: Parse a sentence based on English grammar
img: assets/img/parser.png
importance: 6
category: personal
---

<div class="row">
<div class="col">
    <a class="btn btn-outline-light" href="https://github.com/javkhlantugs/parser">Code</a>
    </div>
</div>

# About

A common task in natural language processing is parsing, the process of determining the structure of a sentence. This is useful for a number of reasons: knowing the structure of a sentence can help a computer to better understand the meaning of the sentence, and it can also help the computer extract information out of a sentence. In particular, it’s often useful to extract noun phrases out of a sentence to get an understanding for what the sentence is about.

This project is about using the context-free grammar formalism to parse English sentences to determine their structure. In a context-free grammar, we repeatedly apply rewriting rules to transform symbols into other symbols. The objective is to start with a nonterminal symbol S (representing a sentence) and repeatedly apply context-free grammar rules until we generate a complete sentence of terminal symbols (i.e., words). The rule S -> N V, for example, means that the S symbol can be rewritten as N V (a noun followed by a verb). If we also have the rule N -> "Holmes" and the rule V -> "sat", we can generate the complete sentence "Holmes sat.".

{% include figure.html path="assets/img/parser.png" title="example image" class="img-fluid rounded z-depth-1" %}
