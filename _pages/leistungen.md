---
layout: default
title:  Leistungen
lang: de
ref: services
permalink: "/leistungen/"
---
# {{ page.title }}

<ul>
{% for service in site.services[page.lang] %}
  <li><b>{{ service.name }}</b></li>
  <ul>
  {% for section in service.sections %}
    <li><a href='{{ service.id }}_{{ section.href_base }}_{{ page.lang }}' class='service_href'>{{ section.name }}</a></li>
  {% endfor %}
  </ul>
{% endfor %}
</ul>
