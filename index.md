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

<!-- Argh !! UGLY html -->
<!-- otherwise problem with fonts of Research etc. -->

<div class="section list">
  <h1>Research</h1>
  <p class="excerpt">
  My day job is as a
  <a href="/work/">
  Postdoctoral Research Fellow
  </a>
  in computational acoustic and electromagnetism
  at
  <a href="http://www.puc.cl">
  Pontifica Universidad Catolica de Chile</a>.
  </p>

  <p></p>

  <p class="excerpt">
  See my
  <a href="/work/pub.html">
  publications
  </a>
  or my
  CV
  </a>
  (<a href="/about/CV_tournier.pdf">pdf</a>)
  for a concrete overview.
  </p>

  <p></p>

  <h1>Blogs</h1>
  <p class="excerpt">
  I keep a kind of
  <a href="/blog/">
  blog
  </a>
  about my current thoughts.
  It is only my personal notes
  or some small <s>Post-it</s> "repositionable notes" for myself.
  </br>Recent posts include:
  <p>
  {% for post in site.categories.blog limit:3 %}
  <ul class="compact recent">
  <li>
	<a href="{{ post.url }}" title="{{ post.excerpt }}">{{ post.title }}</a>
		<span class="date">{{ post.date | date_to_string }}</span>
		</li>
		</ul>
		{% endfor %}
		<!-- try to make this compact list in pure markdown. -->
		<!-- {% for post in site.categories.blog limit:3 %} -->
		<!-- * [{{ post.title }}]({{ post.url }}) -->
		<!-- {% endfor %} -->
		</p>

  <h1>Misc</h1>
  <p class="excerpt">
  I barely use Social Network,
  I mean,

  {% highlight python %}
for SocialNetwork in [Facebook, Twitter, Phone, And-So-On]:
    if find(me, SocialNetwork):
        return not me + noise()
  {% endhighlight %}


  Email me: <b>simon</b> DOT <b>tournier</b> AT <b>gmail</b> DOT <b>com</b>
  </p>
</div>

<p></p>
<p></p>
<center>
</hr>
<em>
Mais il restait le monde entier à explorer<br>
et derrière les montagnes
j'imaginais toujours des horizons sans limites.
</em>
</center>
<center>
<a href="http://www.cpt.univ-mrs.fr/~rovelli/">Carlo Rovelli</a>
<b>in</b> Qu'est-ce que le temps ? Qu'est-ce que l'espace ?
</center>
