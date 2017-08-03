---
layout: default
title:  Backends - Architecture
lang: en
permalink: "/services/backends/architecture_en/"
lang_ref: services_backends_architecture
---

### Architecture?
Yes, Architecture. It's the way your components are put together and interact in your system. For example:

- Databases can be clustered, sharded and/or replicated, and whatever else the kids are doing these days
- Application servers can be request based or have standing connections, or both
- Different components will handle different aspects of the system (user management, chat, content delivery, etc)
- There usually are public and private networks, restricted shell access to both, firewalls, and so on
- You want to avoid "single point of failures" at all times
- Some services will be load balanced, some maybe not

So, when it comes to backend systems, is vital to ask yourself a couple of questions before you start coding, for instance:

- What is it supposed to do (the most obvious, most overlooked question)?
- What data format is best when communicating with the front end?
- Do I have a REST API or do I have standing connections, or both?
- How many concurrent users will I have?
- How quickly do I want to scale up in case of a traffic spike?
- Do I want to tolerate downtimes?
- Will there be different "Realms", i.e. instances of my backend in different locations?
- Do I want to outsource LiveOps completely?
- How frequent do I want to deploy new changes?

And that is just a few. Not all of them can be be answered up front, but from the answers the <em>Architecture</em> of your system will evolve. They will point to vital aspects of the various components, like, what database do we want, what server framework, etc.

I can help you by asking the above questions (repeatedly if necessary) and by outlining the resulting systems from there. This is not a one-off thing, either. It is part of the whole development cycle. Sometimes answers change, and therefore systems, but that's OK (mostly).
