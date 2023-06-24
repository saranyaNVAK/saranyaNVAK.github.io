---
layout: archive
title: "Work Experience"
permalink: /projects/
author_profile: true
---

<style>
  body {
    background-image: url('https://github.com/maitrey-gramo/maitrey-gramo.github.io/assets/111958072/0d639ecc-ba0b-43fc-a059-f701c14ee89a');
    background-repeat: no-repeat;
    background-attachment: fixed; 
    background-size: cover;
  }
</style>

{% include base_path %}

{% for post in site.projects reversed %}
  {% include archive-single.html %}
{% endfor %}
