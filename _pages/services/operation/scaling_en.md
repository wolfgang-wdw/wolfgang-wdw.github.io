---
layout: service-detail
title:  Operation - Scaling
lang: en
permalink: "/services/operation/scaling_en/"
lang_ref: services_operation_scaling
previous: services_operation_monitoring
next: services_coaching_backends
---
"Will this scale" is a good question to ask, despite it being [made fun of](https://medium.com/conquering-corporate-america/10-tricks-to-appear-smart-during-meetings-27b489a39d1a).

Scaling is the act of increasing the resources of a running system, in order to accommodate an increase in load (usually created by traffic from your users).  
In almost every case, you want to do this with as little downtime or disruption as possible.


Scalability of all systems involved should be considered as early as possible in development.

Some things are easy to scale, other things are hard to scale. It's easy, trivial even, to scale a fleet of load balanced, restful application servers. It's harder to scale systems where the state is shared across instances, like databases or servers with standing connections to clients.

Sometimes you also want to scale a system back down, so it is useful to think about this beforehand as well, in order avoid unnecessary expenses.

### What I can do for you
The goal is to make scaling just a matter of how much coin you insert into your hosting provider. To inch closer to this goal, I can help you with:
- Architectural decisions
: Many scaling problems can be solved or made irrelevant by early decisions in conjunction with system requirements.

- To automate or not to automate
: Scaling can be done automatically, in response to predefined rules, or by hand. This is not equally easy for all components of the system. Strategic decisions on the necessary degree of automation can simplify development considerably.

- Build scalability into an existing system
 : This can be tricky, but I can do tricky. I can have a look and give you recommendations.
