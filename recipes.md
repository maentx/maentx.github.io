---
layout: recipe-landing
title: Recipes
---
<ul>
  {% for recipe in site.recipes %}
    <li>
      <h2><a href="{{ recipe.url }}">{{ recipe.title }}</a></h2>
    </li>
  {% endfor %}
</ul>
