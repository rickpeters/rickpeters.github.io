---
layout: post
title: Gaat Jekyll werken voor een documentatiesite?
---

Natuurlijk gaat dat werken, de vraag is meer hoeveel moeite het gaat kosten om het te introduceren
en in te richten.

Werkwijze:
* svn of git repository
* machine met vereiste tools voor jekyll (we hebben geen github-pages hosting)
* jekyll generatie vanuit jenkins CI job
* publicatie van `_site` naar een webserver

Voordelen:
* documentatie is netjes geversioneerd
* publicatie kan gecontroleerd als onderdeel van een release worden uitgevoerd
* moderne look-and-feel
* geen wiki beperkingen
* onderhoud van documentatie met voor devops bekende tools (vi, markdown editor)
* site kan worden onderhouden middels branching en merging of bijv. in svn middels activering van tag

Dit wordt een succes!
