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
    <li><a href='{{ section.href }}' class='service_href'>{{ section.name }}</a></li>
  {% endfor %}
  </ul>
{% endfor %}
</ul>


<!--
* **Code**
  * Backend systems
  * Code cleanup
  * Code rewrite
  * Automation
* **Operation**
  * Deployment
  * Monitoring
  * Cloud/Serverless computing
  * Systems Lifecycle
  * Continuous Integration
  * Change management  
* **Coaching**
* **Consulting**
* **Leadership** -->
