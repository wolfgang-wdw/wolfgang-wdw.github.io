---
layout: default
title:  Backends - Architecture
lang: en
permalink: "/services/backends/architecture_en/"
lang_ref: services_backends_architecture
previous: services_backends_code
next: services_backends_automation
---
{% include page_nav.html %}
### Architecture?
With architecture, I mean the way the components of the system are put together. For example:

- Databases can be clustered, sharded and/or replicated, and whatever else the kids are doing these days
- Application servers can be request based or have standing connections, or both
- Different components will handle different aspects of the system (user management, chat, content delivery, etc)
- There usually are public and private networks, restricted shell access to both, firewalls, and so on
- You want to avoid "single point of failures" at all times
- Some services will be load balanced, some maybe not

### What can I do for you?
So for your backend system, I will keep asking a couple of questions, for instance:

- What is it supposed to do (the most obvious, most overlooked question)?
- What data format is best when communicating with the front end?
- Do I have a REST API or do I have standing connections, or both?
- How many concurrent users will I have?
- How quickly do I want to scale up in case of a traffic spike?
- Do I want to tolerate downtimes?
- Will there be different "Realms", i.e. instances of my backend in different locations?
- Do I want to outsource LiveOps completely?
- How frequent do I want to deploy new changes?

Not all of these questions can be be answered up front, but from the answers the <em>Architecture</em> of your system will evolve. They will point to vital aspects of the various components, like, what database do we want, what server framework, etc.
