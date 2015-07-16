---
layout: page
title: Notebooks
permalink: /notebooks/
---

{% for notebook in site.data.mynotebooks %}
* {{notebook | jsonify }}
{% endfor %}
