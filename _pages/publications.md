---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

<style>
  body {
    background-image: url('https://github.com/maitrey-gramo/maitrey-gramo.github.io/assets/111958072/0d639ecc-ba0b-43fc-a059-f701c14ee89a');
    background-repeat: no-repeat;
    background-attachment: fixed; 
    background-size: cover;
  }

  #rcorners {
    border-radius: 10px;
    background: rgba(255, 255, 255, 0.5);
    background-position: left top;
    background-repeat: repeat;
    padding: 10px;
  }
</style>

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  <p id="rcorners">{% include archive-single.html %}</p>
{% endfor %}
