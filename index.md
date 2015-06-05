---
layout: archive
permalink: /
title: "On Music"
excerpt:
image:
  feature: background.jpg
id: home
---

On Music is the personal website of [Jessica Moseley]({{ site.url }}/about/), a pianist, music theorist, and educator from Buffalo, New York who enjoys eating chicken wings, Skyline chili and making music --- *usually not at the same time*.
{:.shorten}

---

### [Piano Studio]({{ site.url }}/studio/)

I have more than a decade of experience teaching piano to students as young as 4 and as old as 70 --- in conservatories, private universities, and community music schools. I teach 30, 45, and 60 minute lessons at my private studio in Elmwood Village, or at your

[My studio](/studio/) is now accepting students for the summer! [Contact me!](/studio/contact) 

---

### [Thoughts of Mine]({{ site.url }}/blog/)

<div class="tiles">
{% for post in site.categories.blog limit:4 %}
	{% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<!-----

### [Words I've Written]({{ site.url }}/articles/)

<div class="tiles">
{% for post in site.categories.articles limit:4 %}
  {% include post-grid.html %}
{% endfor %}
</div><!-- /.tiles -->

<!-----

### [Pictures I've taken]({{ site.url }}/pictures/)

<ul class="th-grid-full">
{% for post in site.categories.pictures limit:8 %}
  <li><a href="{{ site.url }}{{ post.url }}" title="{{ post.title }}"><img src="{{ site.url }}/images/{{ post.image.thumb }}" alt="thumbnail image"></a></li>
{% endfor %}
</ul>
-->