---
layout: service-detail
title:  Development - Architecture
lang: en
permalink: "/services/development/architecture_en/"
lang_ref: services_development_architecture
previous: services_development_backends
next: services_development_automation
---
With architecture, I mean the way the components of the system are put together. For example:

- Databases can be clustered, [sharded](https://en.wikipedia.org/wiki/Shard_(database_architecture)) and/or replicated, and whatever else the kids are doing these days.
- Application servers can be [REST](https://en.wikipedia.org/wiki/Representational_State_Transfer) based or have standing connections, or both.
- Different components will handle different aspects of the system (user management, chat, content delivery, etc).
- There usually are public and private networks, restricted shell access to both, firewalls, and so on.
- You want to avoid [Single point of failures](https://en.wikipedia.org/wiki/Single_point_of_failure) at all times.
- Some services will be load balanced, some will not.

### What I can do for you
I will keep asking a couple of questions, for instance:
- What is your backend supposed to do (the most obvious, most overlooked question)?
- Which data formats will be used when communicating with the front end?
- Do you want a REST API or do you want standing connections, or both?
- How many concurrent users will you have?
- How quickly do you want to scale up in case of a traffic spike?
- How many scheduled downtimes are you willing to tolerate?
- Will there be different "Realms", i.e. instances of your backend in different locations?
- Do you need to operate the live backend yourself?
- How frequent do you want to deploy new changes?

Not all of these questions can be be answered up front, but from the answers the <em>Architecture</em> of your system will evolve.   
