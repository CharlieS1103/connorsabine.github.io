---
layout: page
title: Games
permalink: /games/
image: '/images/GamingPageBackground.png'
---

<div class="container">
  <div class="row">
    <div class="col col-12">
      <div class="container__inner">
        <div class="row grid">
          {% if site.posts.size > 0 %}
            {% for post in paginator.posts %}
              {% include article-content.html %}
            {% endfor %}
          {% endif %}
        </div>
      </div>
    </div>
  </div>
</div>

