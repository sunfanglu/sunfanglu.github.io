---
layout: archive
title: "简历"
permalink: /zh/cv/
author_profile: true
lang: zh
lang_ref: cv
---

{% include base_path %}

教育背景
======
* （待填写）

工作经历
======
* （待填写）

技能
======
* （待填写）

论文
======
  <ul>{% for post in site.publications reversed %}
    {% assign item_lang = post.lang | default: "en" %}
    {% if item_lang == page.lang %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

演讲
======
  <ul>{% for post in site.talks reversed %}
    {% assign item_lang = post.lang | default: "en" %}
    {% if item_lang == page.lang %}
      {% include archive-single-talk-cv.html %}
    {% endif %}
  {% endfor %}</ul>

教学
======
  <ul>{% for post in site.teaching reversed %}
    {% assign item_lang = post.lang | default: "en" %}
    {% if item_lang == page.lang %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>

服务与职务
======
* （待填写）
