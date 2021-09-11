---
layout: default-no-header
title: Tales of a Consultant Career
---
<style>
ul {
    font-family: 'Titillium Web', sans-serif;
}
li {
    list-style: none;
    transition: background-color 0.2s;
    padding: 10px;
    margin-bottom: 30px;
}
li:hover {
    background-color: #cacaca; 
}
ul.post-list a {
    color: #595353;
    text-decoration: none;
}
.post-description {
    font-size: 16pt;
}
</style>
<ul class="post-list">
  {% for post in site.categories.tales %}
    <a href="{{ post.url }}">
    <li class="post-element">
        <h2 class="post-title">{{ post.title }}</h2>
        <p class="post-description">{{ post.description }}</p>
    </li></a>
  {% endfor %}
</ul>
