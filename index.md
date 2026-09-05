---
layout: default
title: Spatial Signals
---

<section class="intro">
  <p class="eyebrow">Spatial Signals / Пространственный радар</p>
  <h1>GeoAI, geospatial и digital twins без новостного шума</h1>
  <p class="lede">Еженедельный разбор сильных сигналов: что реально изменилось, с чем это сравнивать, почему это важно и какие продуктовые возможности из этого следуют.</p>
  <p class="lede">Публичный архив выпусков собирается из утвержденных материалов и обновляется автоматически через GitHub Pages.</p>
</section>

<section class="issue-list">
  <h2>Последние выпуски</h2>
  {% if site.posts.size > 0 %}
    {% for post in site.posts limit: 6 %}
      <article class="issue-card">
        <div class="issue-date">Неделя {{ post.date | date: "%V" }} · {{ post.date | date: "%d.%m.%Y" }}</div>
        <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
        {% if post.subtitle %}<p>{{ post.subtitle }}</p>{% elsif post.excerpt %}<p>{{ post.excerpt | strip_html | truncate: 220 }}</p>{% endif %}
      </article>
    {% endfor %}
    <p><a href="{{ '/archive/' | relative_url }}">Открыть архив по месяцам и неделям →</a></p>
  {% else %}
    <p class="empty-state">Первый выпуск появится здесь после утверждения в редакционном review.</p>
  {% endif %}
</section>
