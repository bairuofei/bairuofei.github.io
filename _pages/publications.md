---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% assign show_preprints = false %}
{% if show_preprints %}
Preprints
------
{% endif %}
{% for post in site.publications reversed %}
  {% if post.status == "preprint" %}
    {% if post.include_on_website %}
      {% include publication-single.html %}
    {% endif %}
  {% endif %}
{% endfor %}

Published Articles
------
{% for post in site.publications reversed %}
    {% unless post.type contains "thesis" %}
      {% if post.include_on_website %}
        {% include publication-single.html %}
      {% endif %}
    {% endunless %}
{% endfor %}


