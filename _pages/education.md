---
title: Обучение в Dive Zone Club
layout: single
classes: wide
permalink: /education
data:
    - url: /beginners
      title: Начинающим
      image_path: /assets/img/%D0%BD%D0%B0%D1%87%D0%B8%D0%BD%D0%B0%D1%8E%D1%89%D0%B8%D0%BC.jpg
    - url: /kids-diving
      title: Дайвинг для детей
      image_path: /assets/img/дети и дайвинг.jpg
    - url: /reactivate
      title: Восстановление навыков
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /discover-new-diving
      title: Discover new diving
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /continuing
      title: Продолжающим
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /efr
      title: Курсы первой помощи
      image_path: /assets/img/EFR_PS.jpg
    - url: /pro
      title: Стань профессионалом
      image_path: /assets/img/стань про.jpg
    - url: /specializations
      title: Специализации
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