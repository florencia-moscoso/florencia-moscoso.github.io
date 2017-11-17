---
layout: default
description: "Sitio web de Florencia Viviana moscoso"
id: home
---

<div class="hero">
  <div class="hero-inner">
    <img class="hero-logo" src="/img/small.jpg" alt="">
    <h1>{{ site.title }}</h1>
    <p>{{ site.description }}</p>
  </div>
</div>

<div class="articles">
  <div class="articles-inner">
    <h2>Mis publicaciones</h2>
    <ul>
      {% for article in site.categories.publicaciones %}
        <li>
          <a href="{{ article.url }}"> {{ article.title }}</a>
          {% if article.fecha_publicacion %}
            - <small>{{ article.fecha_publicacion }}</small>
          {% endif %}
          {% if article.autores %}
            - <small>{{ article.autores }}</small>
          {% endif %}
        </li>
      {% endfor %}
    </ul>
  </div>
</div>
