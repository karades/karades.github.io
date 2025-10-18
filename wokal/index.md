---
layout: default
title: Blog Wokalny - Nadchodzące Koncerty
permalink: /wokal/
---

# Moja Twórczość Wokalna
Tutaj znajdziesz próbki mojego głosu...

# Archiwalne Koncerty

Poniżej znajdziesz listę wszystkich moich wpisów...

{% for post in site.categories.wokal %}
    <div class="post-listing">
        <h2><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h2>
        <p class="post-meta">{{ post.date | date: "%B %d, %Y" }}</p>
        <p>{{ post.excerpt | strip_html | truncatewords: 30 }}</p>
        <a href="{{ post.url | relative_url }}">Czytaj więcej...</a>
        <hr>
    </div>
{% endfor %}

[← Wróć do strony głównej](/ 'Strona główna')