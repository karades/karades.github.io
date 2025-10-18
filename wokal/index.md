---
layout: default
title: Wokal - Moja Twórczość
---

# Moja Twórczość Wokalna

Tutaj znajdziesz próbki mojego głosu, covery i linki do moich nagrań.

# Archiwalne Koncerty

Poniżej znajdziesz listę wszystkich moich wpisów dotyczących występów, recenzji i ogłoszeń.

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