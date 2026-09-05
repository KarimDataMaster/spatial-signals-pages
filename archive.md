---
layout: default
title: Архив выпусков
permalink: /archive/
---

<section class="intro archive-intro">
  <p class="eyebrow">Spatial Signals</p>
  <h1>Архив выпусков</h1>
  <p class="lede">Все опубликованные выпуски по месяцам и неделям. Новые выпуски добавляются автоматически после утверждения.</p>
</section>

{% if site.posts.size > 0 %}
  {% assign month_groups = site.posts | group_by_exp: "post", "post.date | date: '%Y-%m'" %}
  <section class="archive-list">
    {% for group in month_groups %}
      {% assign year = group.name | slice: 0, 4 %}
      {% assign month = group.name | slice: 5, 2 %}
      {% case month %}
        {% when '01' %}{% assign month_name = 'Январь' %}
        {% when '02' %}{% assign month_name = 'Февраль' %}
        {% when '03' %}{% assign month_name = 'Март' %}
        {% when '04' %}{% assign month_name = 'Апрель' %}
        {% when '05' %}{% assign month_name = 'Май' %}
        {% when '06' %}{% assign month_name = 'Июнь' %}
        {% when '07' %}{% assign month_name = 'Июль' %}
        {% when '08' %}{% assign month_name = 'Август' %}
        {% when '09' %}{% assign month_name = 'Сентябрь' %}
        {% when '10' %}{% assign month_name = 'Октябрь' %}
        {% when '11' %}{% assign month_name = 'Ноябрь' %}
        {% when '12' %}{% assign month_name = 'Декабрь' %}
      {% endcase %}

      <div class="archive-month">
        <h2>{{ month_name }} {{ year }}</h2>
        {% for post in group.items %}
          <article class="issue-card">
            <div class="issue-date">Неделя {{ post.date | date: "%V" }} · {{ post.date | date: "%d.%m.%Y" }}</div>
            <h3><a href="{{ post.url | relative_url }}">{{ post.title }}</a></h3>
            {% if post.subtitle %}<p>{{ post.subtitle }}</p>{% elsif post.excerpt %}<p>{{ post.excerpt | strip_html | truncate: 220 }}</p>{% endif %}
          </article>
        {% endfor %}
      </div>
    {% endfor %}
  </section>
{% else %}
  <p class="empty-state">Первый выпуск появится здесь после финального утверждения.</p>
{% endif %}
