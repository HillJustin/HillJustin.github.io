---
layout: default
title: Holy Terrain Art, a Podcast
---

# {{ site.podcast.title }}: A Podcast

### *{{ site.podcast.subtitle}}*

Episodes of *Holy Terrain Art* are also available on [Apple Podcasts](https://podcasts.apple.com/us/podcast/holy-terrain-art/id1841546111){:target="_blank" rel="noreferrer noopener"} and [Spotify Podcasts](https://open.spotify.com/show/6DVqh1VNayxnUWucSoIG9h/){:target="_blank" rel="noreferrer noopener"}. Video episodes are also available on [YouTube](https://youtube.com/@HolyTerrainArt/){:target"_blank" rel="noreferrer noopener"}.

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
