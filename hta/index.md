---
layout: default
title: Holy Terrain Art, a Podcast
---

# {{ site.podcast.title }}: A Podcast

### *{{ site.podcast.subtitle}}*

Episodes of *Holy Terrain Art* are also available on [Apple Podcasts](https://podcasts.apple.com/us/podcast/holy-terrain-art/id1841546111){:target="_blank" rel="noreferrer noopener"} and [Spotify Podcasts](https://open.spotify.com/show/6DVqh1VNayxnUWucSoIG9h/){:target="_blank" rel="noreferrer noopener"}. Video episodes are also available on [YouTube](https://youtube.com/@HolyTerrainArt/){:target"_blank" rel="noreferrer noopener"}.


### *What is Holy Terrain Art?*

{{ site.podcast.description }}


### *Course Syllabi*

Use the syllabi below to match the assigned readings with podcast episodes. As the lecture catalog expands, so too will the course offerings.

* [PHIL 1301: Introduction to Philosophy](/assets/pdfs/hillj-phil-1301-syllabus.pdf)

* [PHIL 1304: Introduction to World Religions](/assets/pdfs/hillj-phil-1301-syllabus.pdf)

* PHIL 2305: Contemporary Ethical Issues [Forthcoming]

* PHIL 2310: The Meaning of Life [Forthcoming]


### *Podcast Lecture Episodes*

{% for post in site.posts %}

<div>
  <ul>
    <li><a href="{{ post.url }}">{{ post.title }}</a></li>
  </ul>
</div>

{% endfor %}
