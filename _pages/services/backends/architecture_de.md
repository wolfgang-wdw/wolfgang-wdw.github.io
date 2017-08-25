---
layout: service-detail
title:  Backends - Architektur
lang: de
permalink: "/services/backends/architecture_de/"
lang_ref: services_backends_architecture
previous: services_backends_code
next: services_backends_automation
---
Wenn ich Architektur sage, meine ich die Zusammensetzung der Komponenten des Systems. Zum Beispiel:
- Datenbanken können in "clustern" oder "shards" gruppiert sein, sie können repliziert sein, usw.
- Applikationsserver können request basiert sein, stehende Verbindungen implementieren, oder beides.
- In der Regel zerfällt Die Applikation in verschiedene Komponenten die verschiedene Aspekte des Systems behandeln (z.B. Benutzerverwaltung, Chat, Content Delivery).
- In der Regel gibt es öffentliche und private Netzwerke, eingeschränkten Shell Zugang, Firewalls, usw.
- [Single points of failure](https://en.wikipedia.org/wiki/Single_point_of_failure) sollten so gut wie möglich vermieden werden.
- Einige Dienste werden load balanced sein, einige nicht.

### What I can do for you
I will keep asking a couple of questions, for instance:

- What is it supposed to do (the most obvious, most overlooked question)?
- What data format is best when communicating with the front end?
- Do you want a REST API or do you want standing connections, or both?
- How many concurrent users will you have?
- How quickly do you want to scale up in case of a traffic spike?
- Do you want to tolerate downtimes?
- Will there be different "Realms", i.e. instances of your backend in different locations?
- Do you need to operate the live backend yourself?
- How frequent do you want to deploy new changes?

Not all of these questions can be be answered up front, but from the answers the <em>Architecture</em> of your system will evolve.   
