---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

자격증
======
* 네트워크관리사 2급
* 리눅스마스터 2급
* 컴퓨터활용능력 2급

수상
======
* K-Digital Training 해커톤 최우수상 (고용노동부 장관상)

언어
======
* 한국어 (원어민)
* 영어 (기본 의사소통 가능)

Skills
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
