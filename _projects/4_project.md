---
layout: page
title: Six Degrees of Kevin Bacon
description: Shortest distance of two actors via movies starred in.
img: assets/img/bacon.jpeg
importance: 4
category: personal
---

<div class="row">
<div class="col">
    <a class="btn btn-outline-light" href="https://github.com/javkhlantugs/movie_star_degrees_of_seperation">Code</a>
    </div>
</div>

# About

According to the [Six Degrees of Kevin Bacon](https://en.wikipedia.org/wiki/Six_Degrees_of_Kevin_Bacon#:~:text=It%20rests%20on%20the%20assumption,or%20fewer%20acquaintance%20links%20apart.) game, anyone in the Hollywood film industry can be connected to Kevin Bacon within six steps, where each step consists of finding a film that two actors both starred in.

This code will find the shortest path between any two actors by choosing a sequence of movies that connect them. 

This code is using [IMDB](https://www.imdb.com)'s database.

# Example

###### Input 1
> Samuel L. Jackson

###### Input 2
> Brad Pitt

###### Output
>2 degrees of separation.<br>
>1: Samuel L. Jackson and Morgan Freeman starred in The Hitman's Wife's Bodyguard<br>
>2: Morgan Freeman and Brad Pitt starred in Se7en
