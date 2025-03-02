---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page shows selected journal articles and conference papers.
For a complete list of my publications, please visit my [Google Scholar profile](https://scholar.google.com/citations?user=1deQ5u4AAAAJ&hl=en&oi=ao) or see my [CV](/files/CV_BaiRuofei.pdf).

<dl id="publications">
  <dt></dt>
  <dd>作者1, 作者2, “论文标题特别长论文标题特别长论文标题特别长”,
      会议/期刊, 年份. <a href="#">[arXiv]</a></dd>

  <dt></dt>
  <dd>作者A, 作者B, “另一篇论文标题”,
      会议/期刊, 年份. <a href="#">[PDF]</a></dd>

  <dt></dt>
  <dd>作者X, 作者Y, “第三篇论文标题”,
      会议/期刊, 年份. <a href="#">[DOI]</a></dd>
</dl>

<script>
  document.addEventListener("DOMContentLoaded", function() {
      let items = document.querySelectorAll("#publications dt");
      items.forEach((dt, index) => {
          dt.textContent = `[${index + 1}]`;
      });
  });
</script>



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

Journal Articles
------
{% for post in site.publications reversed %}
  {% if post.status == "journal"%}
    {% unless post.type contains "thesis" %}
      {% if post.include_on_website %}
        {% include publication-single.html %}
      {% endif %}
    {% endunless %}
  {% endif %}
{% endfor %}

Conference Papers
------
{% for post in site.publications reversed %}
  {% if post.status == "conference"%}
    {% unless post.type contains "thesis" %}
      {% if post.include_on_website %}
        {% include publication-single.html %}
      {% endif %}
    {% endunless %}
  {% endif %}
{% endfor %}

<!-- Theses
======
{% for post in site.publications reversed %}
  {% if post.type contains "thesis" %}
    {% if post.include_on_website %}
      {% include publication-single.html %}
    {% endif %}
  {% endif %}
{% endfor %} -->
