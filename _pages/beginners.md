---
title: Начинающим
layout: single
permalink: /beginners
classes: wide
data:
    - url: /dsd
      title: Discover Scuba Diving / Пробное погружение с аквалангом
      image_path: /assets/img/dsd.jpg
    - url: /owd
      title: Open Water Diver / дайвер открытой воды
      image_path: /assets/img/owd.jpg
    - url: /skin
      title: Skin Diver / погружения на задержке дыхания
      image_path: /assets/img/dive-zone-club-logo.jpg
---

<div class="flex-container images">
    {% for d in page.data %}
        <div class="flex-item">
            <figure>
                <a href="{{ site.url }}{{ site.baseurl }}{{ d.url }}">
                    <img src="{{ site.url }}{{ site.baseurl }}{{ d.image_path }}" />
                </a>
                <figcaption><h3><a href="{{ site.url }}{{ site.baseurl }}{{ d.url }}">{{ d.title }}</a></h3></figcaption>
            </figure>
        </div>
    {% endfor %}
</div>
