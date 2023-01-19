---
title: Historique
displaytext: Historique
layout:  null
tab: true
order: 3
tags: OWASPMTL
---

## **Historique des séances (virtuelles et/ou en présentiel)**
-------------------------------------------------------------------
Les séances ont lieu sur une base minimale mensuelle et se déroulent généralement dans une salle mise à disposition par un sponsor au centre-ville de Montréal.

# 2022

{% assign page_event_2022 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'events/2022'" %}

{% for page in page_event_2022 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}

<br>
<br>

# 2023

{% assign page_event_2023 = site.pages | sort: 'name' | where_exp: "page", "page.path contains 'events/2023'" %}

{% for page in page_event_2023 %}
* [{{ page.title }}]({{site.baseurl }}{{ page.url }})
{% endfor %}