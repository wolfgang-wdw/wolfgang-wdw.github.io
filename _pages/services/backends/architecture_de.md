---
layout: service-detail
title:  Backends - Architektur
lang: de
permalink: "/services/backends/architecture_de/"
lang_ref: services_backends_architecture
previous: services_backends_code
next: services_backends_automation
---
Mit Architektur meine ich die grobe Zusammensetzung der Komponenten des Systems. Zum Beispiel:
- Datenbanken können in "clustern" oder "[shards](https://en.wikipedia.org/wiki/Shard_(database_architecture))" gruppiert sein, sie können repliziert sein, usw.
- Applikationsserver können REST basiert sein, stehende Verbindungen implementieren, oder beides.
- In der Regel zerfällt Die Applikation in verschiedene Komponenten die verschiedene Aspekte des Systems behandeln (z.B. Benutzerverwaltung, Chat, Content Delivery).
- Es gibt öffentliche und private Netzwerke, eingeschränkten Shell Zugang, Firewalls, usw.
- [Single points of failure](https://en.wikipedia.org/wiki/Single_point_of_failure) sollten so gut wie möglich vermieden werden.
- Einige Dienste werden load balanced sein, einige nicht.

### Was ich für Sie tun kann
Ich werde wiederholt Fragen stellen, wie zum Beispiel:
- Was soll das Backend tun (die offensichtlichste, oft übersehene Frage)?
- Welches Datenformate kommen bei der Kommunikation mit den Frontend zum Einsatz?
- Braucht es eine REST API, stehende Verbindungen, oder beides?
- Wie viele Benutzer sollen gleichzeitig bedient werden können?
- Wie schnell wollen Sie hoch-skalieren können, in Falle von Traffic-Spitzen?
- Wie viele vorgesehene Abschaltzeiten wollen sie tolerieren?
- Werden unterschiedliche Instanzen Ihres Backends in verschiedenen Örtlichkeiten stehen?
- Wollen/Müssen Sie Ihr Live-Backend selbst operieren?
- Wie oft werden sie Änderungen einspielen?

Nicht alle dieser Fragen können im Vorfeld beantwortet werden, aber die Antworten werden die <em>Architektur</m> Ihres Systems nach und nach entstehen lassen.
