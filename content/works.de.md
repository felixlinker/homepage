---
title: "Arbeiten & Veröffentlichungen"
date: 2017-12-22T00:09:06+01:00
draft: false
---

## Industrial Benchmark for Fuzzy Particle Swarm Reinforcement Learning

### Beschreibung

In diesem Projekt habe ich den Ansatz aus *Hein et al., 2017* namens *Fuzzy Particle Swarm Reinforcement Learning* (FPSRL) zur Optimiung von Controller Strategien umgesetzt, implementiert und gebenchmarked.
Die Benchmark wurde durch die *Industrial Benchmark* (IB) realisiert, der Methode folgend, die die Autoren selbst in *Hein, Udluft, Runkler, 2018* zum Benchmarken eines ähnlichen Ansatzes, der Genetische Programmierung anstelle von Partikelschwarm Optimierung verwendet, vorschlugen.
Der Code wurde in python geschrieben.

[*Link zum github repository (mit Quellen)*](https://github.com/felixlinker/IB_FPSRL)

[*Zusammenfassung der Resultate*](/doc/ib_fpsrl.pdf)

## AGM-Style Contraction in Dung-Logics for Argumentation Frameworks

### Beschreibung

Hierbei handelt es sich um meine Bachelorarbeit, in der es um [Argumenation Frameworks](https://en.wikipedia.org/wiki/Argumentation_framework) und die [AGM theory of belief revision](https://en.wikipedia.org/wiki/Belief_revision) geht.
Ich erweitere [eine Veröffentlichung von R. Baumann und G. Brewka](https://www.informatik.uni-leipzig.de/~baumann/papers/ijcaiBR.pdf), in der Implementierungen für Expansion- und Revision-Operatoren in Dung-Logiken für Argumentation Frameworks angegeben wurden.
In meiner Arbeit zeige ich, dass es keinen Contraction-Operator für Dung-Logiken geben kann.

[*Download*](/doc/agm_contraction_ba.pdf)

## Facebook Network Analysis of News Pages

### Beschreibung

Im Wintersemester 2016/17 war ich Leiter des Projekts "Facebook Network Analysis of News Pages" im Rahmen des Moduls *Introduction to Digital Humanities*.
Unser Ziel war es, die Behauptung zu untersuchen, dass die meisten Leute facebook durch ihre filter-bubble bzw. echo-chamber erleben.
Indem wir frei zugängliche Daten der facebook Graph API in der Graph Datenbanken [ArangoDB](https://www.arangodb.com/) anonym und temporär speicherten, fanden wir heraus, dass es tatsächlich solche filter-bubbles gab, die im Falle Deutschlands innerhalb des klassischen, politischen Spektrums verortet werden können.

[*Download*](/doc/pt_pr.pdf)

## TWIG

### Beschreibung

2016 modellierte und implementierte ich einen [RDF](https://de.wikipedia.org/wiki/Resource_Description_Framework)-benchmark Generator, der darauf abzielt, dem Benutzer einen pseudo-random, lebensnahen RDF-Datensatz zu generieren, mit dem RDF-Algorithmen getestet werden können.
Er kann über einen Seed konfiguriert werden und simuliert Twitter, wovon die Ergebnisse in RDF gespeichert werden.

[*Link zum github-repository*](https://github.com/dice-group/TWIG)
