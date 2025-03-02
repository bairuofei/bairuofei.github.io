---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

This page shows selected journal articles and conference papers.
For a complete list of my publications, please visit my [Google Scholar profile](https://scholar.google.com/citations?user=1deQ5u4AAAAJ&hl=en&oi=ao) or see my [CV](/files/CV_BaiRuofei.pdf).

.publications {
    counter-reset: pub-counter; /* 初始化计数器 */
}

.publication {
    display: flex;
    align-items: flex-start;
    margin-bottom: 1.2em;
    counter-increment: pub-counter; /* 每个 .publication 增加 1 */
}

.publication::before {
    content: "[" counter(pub-counter) "]"; /* 自动生成 [1], [2], [3] */
    flex: 0 0 2em; /* 固定宽度，确保对齐 */
    text-align: right;
    padding-right: 0.5em;
}

.pub-content {
    flex: 1; /* 让正文占据剩余空间 */
    text-align: justify;
}

<div class="publications">
    <div class="publication">
        <p class="pub-content">
            作者1, 作者2, 作者3, “论文标题特别长论文标题特别长论文标题特别长论文标题特别长论文标题特别长”,
            会议/期刊, 年份. <a href="#">[arXiv]</a>
        </p>
    </div>

    <div class="publication">
        <p class="pub-content">
            作者A, 作者B, “另一篇论文标题”,
            会议/期刊, 年份. <a href="#">[PDF]</a>
        </p>
    </div>
</div>



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
