---
layout: general
title: Home

section: Home
---

<img class='inset right' src='/images/mountain.jpg' title='simon'
alt='Valley of the huts -- Pyrénées' width='220px' />

Welcome
=======

If you don't know [me](/about/), I'm
usually
trekking somewhere
or on the road elsewhere ;
or sometimes  close to my computer
and interested by 
[computational problems arising from engineering world](/work/),
or just by [42](/code/) ;
I'm French, epicurean, coffee addict,
fan of bad movies, ...


+--{.section}
Research
========
My day job is as a [Postdoctoral Research Fellow](/work/) 
in computational acoustic and electromagnetism
at [Pontifica Universidad Catolica de Chile](http://www.puc.cl).

See my 
[publications](/work/pub.html) 
or my [CV](/about/CV.html) ([pdf](/about/CV_tournier.pdf))
for a concrete overview.
=--

+--{.section}
Blogs
=====
I keep a kind of [blog](/blog) about my current thoughts.
It is only my personal notes 
or some small <s>Post-it</s> "repositionable notes" for myself.   
Recent posts include:
{% for post in site.categories.iem limit:3 %}
<ul class="compact recent">
<li>
	<a href="{{ post.url }}" title="{{ post.excerpt }}">{{ post.title }}</a>
	<span class="date">{{ post.date | date_to_string }}</span> 
</li>
</ul>
{% endfor %}
=--

+--{.section}
Misc
=====
I barely use Social Network,     
I mean,

{% highlight python %}
for SocialNetwork in [Facebook, Twitter, Phone, And-So-On]: 
    if find(me, SocialNetwork):   
       return not me + noise()
{% endhighlight %}

Email me: **simon** |DOT| **tournier** |AT| **gmail** |DOT| **com**
=--

- - - - 
<center>
<em>
Mais il restait le monde entier à explorer</br>
et derrière les montagnes
j'imaginais toujours des horizons sans limites.
</em>
</center>
<center>
<a href="http://www.cpt.univ-mrs.fr/~rovelli/">Carlo Rovelli</a>
<b>in</b> Qu'est-ce que le temps ? Qu'est-ce que l'espace ?
</center>
