---
layout: page
permalink: /diary/
title: My Diary
nav: false
---

<h2>My Diary</h2>

{% for file in site.static_files %}
    {% if file.path contains '我和她们的故事-散文' and file.path contains '.md' %}
    * [{{ file.basename }}]({{ file.basename }})
    {% endif %}
{% endfor %}