---
layout: default
title:  Kontakt
lang: de
lang_ref: contact
permalink: "/contact_de/"
---

<div class="container-fluid">

<img
  src="/img/headshot.jpg"
  alt="Wolfgang Deutsch"
  class="img-circle img-responsive center-block headshot"
/>

<div class="contact-headline">Wolfgang Deutsch</div>
<div class="contact-subtitle">Senior Software Engineer</div>

<div class="contact-links">
  {% for c in site.contact %}
    <a href="{{c.link}}">{{ c.name }}</a>
    {% if forloop.last == false %}
    &bull;
    {% endif %}
  {% endfor %}
</div>
