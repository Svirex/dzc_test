---
title: Продолжающим
layout: single
classes: wide
permalink: /continuing
data:
    - url: /aowd
      title: PADI Advanced Open Water Diver / продвинутый дайвер открытой воды
      image_path: /assets/img/aowd.jpg
    - url: /rescue
      title: PADI Rescue Diver / дайвер-спасатель
      image_path: /assets/img/rescue.jpg
    - url: /master-scuba
      title: Master Scuba Diver
      image_path: /assets/img/msd.jpg
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