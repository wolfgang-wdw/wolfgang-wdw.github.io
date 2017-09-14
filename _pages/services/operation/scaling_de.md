---
layout: service-detail
title:  Betreibung - Skalierung
lang: de
permalink: "/services/operation/scaling_de/"
lang_ref: services_operation_scaling
previous: services_operation_monitoring
next: services_coaching_backends
---
Unter Skalierung verstehe ich das strategische Erhöhen der Ressourcen eines laufenden Systems, um eine Steigung in der Belastung (normalerweise durch Datenverkehr von den Benutzern) aufzufangen.  
Es sollen dabei so wenig und so kurze Ausfälle wie möglich entstehen.

Die Skalierbarkeit aller beteiligten Systeme sollte so früh wie möglich in der Entwicklung bedacht werden.

Dabei gibt es Dinge, die einfach zu skalieren sind, und andere die schwerer zu skalieren sind. Es ist leicht, sogar trivial, eine Flotte von Load-Balanced, REST-Basierten Applikationsservern zu skalieren. Es ist schwerer bei Systemen, bei denen der Zustand zwischen den Instanzen eher verschränkt ist, wie z.b. Datenbanken oder Server mit stehenden Verbindungen zu Clients.

### Was ich für Sie tun kann
Ziel ist es, die Skalierung ausschließlich davon abhängig zu machen, wieviele Münzen sie bei Ihrem Hosting Provider einwerfen. Um diesem Ziel näher zu kommen, kann ich Ihnen folgendermaßen helfen:
- Architekturelle Entscheidungen
: Viele Probleme der Skalierbarkeit können durch frühe Entscheidungen anhand von Systemanforderungen gelöst oder irrelevant gemacht werden.

- Automatische oder manuelle Skalierung
: Skalierung kann vollautomatisch passieren, anhand von vordefinierten Regeln. Das ist nicht bei allen Komponenten des Systems leicht möglich. Strategische Entscheidungen über den nötigen Grad der Automatisierung können die Entwicklung sehr vereinfachen.

- Ein bestehendes System skalierbar machen
: Das könnte schwierig sein, aber ich mag schwierig. Ich kann es mir zumindest ansehen und Empfehlungen geben.
