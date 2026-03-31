---
layout: page
permalink: /archive/
title: Posts Archive
---

<div id="archives">
  <section id="archive">
    {% for post in site.posts %}
      {% capture year %}{{ post.date | date: '%Y' }}{% endcapture %}
      {% capture month %}{{ post.date | date: '%B %Y' }}{% endcapture %}

      {% if forloop.first %}
        <h2 style="text-align:left;">{{ year }}</h2>
        <ul>
        <h3 style="text-align:left;">{{ month }}</h3>
      {% else %}
        {% capture nyear %}{{ post.next.date | date: '%Y' }}{% endcapture %}
        {% capture nmonth %}{{ post.next.date | date: '%B %Y' }}{% endcapture %}
        {% if year != nyear %}
          </ul>
          <h2 style="text-align:left;">{{ year }}</h2>
          <ul>
        {% endif %}
        {% if month != nmonth %}
          <h3 style="text-align:left;">{{ month }}</h3>
        {% endif %}
      {% endif %}

      <p><b><a href="{{ site.baseurl }}{{ post.url }}">{% if post.title and post.title != "" %}{{ post.title }}{% else %}{{ post.excerpt | strip_html }}{% endif %}</a></b> - {% if post.date and post.date != "" %}{{ post.date | date: "%e %B %Y" }}{% endif %}</p>
    {% endfor %}
    </ul>
  </section>
</div>
