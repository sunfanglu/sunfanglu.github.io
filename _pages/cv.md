---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
lang: en
lang_ref: cv
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)
* M.S. in Jekyll, GitHub University, 2014
* B.S. in GitHub, GitHub University, 2012

Work experience
======
* Spring 2024: Academic Pages Collaborator
  * Github University
  * Duties includes: Updates and improvements to template
  * Supervisor: The Users

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub

* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% assign item_lang = post.lang | default: "en" %}
    {% if item_lang == page.lang %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% assign item_lang = post.lang | default: "en" %}
    {% if item_lang == page.lang %}
      {% include archive-single-talk-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% assign item_lang = post.lang | default: "en" %}
    {% if item_lang == page.lang %}
      {% include archive-single-cv.html %}
    {% endif %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
