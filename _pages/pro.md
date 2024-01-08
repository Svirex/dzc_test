---
title: Стань профессионалом
layout: single
classes: wide
permalink: /pro
data:
    - url: /divemaster
      title: PADI Divemaster / Дайвмастер
      image_path: /assets/img/divemaster.jpg
    - url: /dsd-leader
      title: DSD Leader
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /assistant-instructor
      title: Assistant Instructor PADI / Ассистент инструктора
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /efr-instructor
      title: Emergency First Response Instructor 
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