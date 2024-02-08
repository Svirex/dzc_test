---
title: Спецкурсы
permalink: /specializations-page
classes: wide
data:
    - url: /specializations/aware
      title: Project AWARE
      image_path: /assets/img/aware.jpg
    - url: /specializations/aware-coral
      title: Coral Reef Conservation / сохранение коралловых рифов
      image_path: /assets/img/aware coral.jpg
    - url: /specializations/boat
      title: Boat Diver
      image_path: /assets/img/boat.jpg
    - url: /specializations/deep
      title: Deep Diver / глубокие погружения
      image_path: /assets/img/deep.jpg
    - url: /specializations/dsmb
      title: Delayed Surface Marker Buoy (DSMB) Diver / погружения с поверхностным маркерным буем
      image_path: /assets/img/dsmb.jpg
    - url: /specializations/against-debris
      title: Dive Against Debris / дайверы против мусора
      image_path: /assets/img/dive-againt-debris.jpg
    - url: /specializations/drift
      title: Drift Diver / погружения в условиях течений 
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /specializations/drysuit
      title: Dry Suit Diver / погружения в сухом гидрокостюме
      image_path: /assets/img/dry suit.jpg
    - url: /specializations/ead
      title: Enriched Air Diver / погружения на обогащённом воздухе
      image_path: /assets/img/ead.jpg
    - url: /specializations/equipment-specialist
      title: Equipment Specialist / специалист по снаряжению
      image_path: /assets/img/equipment-specialist.jpg
    - url: /specializations/eop
      title: Emergency Oxygen Provider / аварийная подача кислорода пострадавшему
      image_path: /assets/img/EOP.jpg
    - url: /specializations/full-face-mask
      title: Full Face Mask / Погружения с полнолицевой маской
      image_path: /assets/img/full-face-mask.png
    - url: /specializations/gas-blender
      title: Gas Blender (Nitrox)
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /specializations/ice
      title: Ice Diver / подлёдные погружения
      image_path: /assets/img/ice.jpg
    - url: /specializations/night
      title: Night Diver / ночные погружения
      image_path: /assets/img/night.jpg
    - url: /specializations/ppb
      title: Peak Performance Buoyancy / мастерское управление плавучестью
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /specializations/search-recovery
      title: Search & Recovery Diver / поиск и подъём затонувших предметов
      image_path: /assets/img/search-and-recovery.jpg
    - url: /specializations/self-reliant
      title: Self-Reliant Diver / самодостаточный дайвер
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /specializations/sidemount
      title: Sidemount Diver / погружения в боковой конфигурации
      image_path: /assets/img/dive-zone-club-logo.jpg
    - url: /specializations/underwater-navigator
      title: Underwater Navigator / подводное ориентирование
      image_path: /assets/img/navigation.jpg
    - url: /specializations/underwater-videographer
      title: Underwater Videographer / Подводная видеосъемка
      image_path: /assets/img/video.jpg
    - url: /specializations/wreck
      title: Wreck Diver / погружения на затонувшие объекты
      image_path: /assets/img/wreck.jpg
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