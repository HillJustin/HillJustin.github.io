---
layout: default
title: Holy Terrain Art, a Podcast
---

# {{ site.podcast.title }}: A Podcast

### *{{ site.podcast.subtitle}}*

*Holy Terrain Art* is also available on [Apple Podcasts](https://podcasts.apple.com/us/podcast/holy-terrain-art/id1841546111){:target="_blank" rel="noreferrer noopener"}, [Castbox](https://castbox.fm/vh/6764982){:target="_blank" rel="noreferrer noopener"}, [Goodpods](https://go.goodpods.com/vub64w){:target="_blank" rel="noreferrer noopener"}, and [Pocketcasts](https://pca.st/15m1la01){:target="_blank" rel="noreferrer noopener"}. Video episodes are also available on [YouTube](https://youtube.com/@HolyTerrainArt/){:target"_blank" rel="noreferrer noopener"}.

<br>


<iframe src="https://castbox.fm/app/castbox/player/id6764982?v=8.22.11&autoplay=0" frameborder="0" width="100%" height="500"></iframe>

<br>


### *What is Holy Terrain Art?*

{{ site.podcast.description }}

<br>


### *Courses*

{% include courses.md %}

<br>


### *Podcast Lecture Episodes*

{% for post in site.posts %}

<ul>
  <div>
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  </div>
</ul>

{% endfor %}

<br>
