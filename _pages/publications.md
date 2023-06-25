---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  body {
    background-image: url('https://github.com/saranyaNVAK/saranyaNVAK.github.io/images/back.jpeg');
    background-repeat: no-repeat;
    background-attachment: fixed; 
    background-size: cover;
  }
</style>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
