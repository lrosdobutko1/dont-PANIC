---
layout: default
title: "Don't Panic!"
description: "A new dev’s descent into indie game development, software development, doubt, and questionable life choices."
permalink: /
author: Lawrence R.
---


## Enjoy the ride, because it's going to get bumpy! 
> 
> ### I lied. It's already bumpy, and it's only going to get worse from here. It's bumps all the way down!
> 
>> "No fine work can be done without concentration and self-sacrifice and toil and doubt."
> 
> So sayeth the great philosopher Max Beerbohm. Or so I am told. You will find no shortage of doubt and toil here as I, a former tradesperson who had had enough of the trades and chose to receive an education in software development, dive into the quagmire (Giggity) of Indy game development, and other projects I find interesting, as I learn to grow as a developer.  
>
> So why a blog? Because learning is hard, and as the smoothest of smooth-brains, I learn best by repeatedly doing a thing, then thinking about that thing, and then writing down words about what I thought about > that thing in the hopes that maybe the thing will stick and I can call that "knowledge".  
> 
> Also, if I have to suffer through the growing pains of being a junior again, I find it just a little bit more bearable if I can make as many other people as possible suffer with me. I'm not *just* a masochist.  

## Posts:  

<ul>
  {% for post in site.posts %}
    <li>
      <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
    </li>
  {% endfor %}
</ul>  

***  

<a href="{{ "/feed.xml" | relative_url }}">RSS</a>  

<link rel="alternate" type="application/rss+xml" title="{{ site.title }}" href="{{ "/feed.xml" | relative_url }}">

