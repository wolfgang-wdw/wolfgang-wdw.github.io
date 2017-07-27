---
layout: default
title:  Services
lang: en
ref: services
permalink: "/services/"
---
# {{ page.title }}

<ul>
{% for service in site.services[page.lang] %}
  <li><b>{{ service.name }}</b></li>
  <ul>
  {% for section in service.sections %}
    {% assign full_href = '/services/'
    | append: service.id
    | append: "_" | append: section.href_base
    | append: '_' | append: page.lang %}
    <li><a href='{{ full_href | relative_url }}' class='service_href'>{{ section.name }}</a></li>
  {% endfor %}
  </ul>
{% endfor %}
</ul>
