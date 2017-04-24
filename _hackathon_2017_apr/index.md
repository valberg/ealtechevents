---
layout: page
title: Introduction
---

{% assign path_elements = page.url | split: "/"  %}
{% assign eventname = path_elements[1] %}
{% assign event = site.collections | where: "label", eventname | first %}

{{ event.title }}
---------------------------------

This hackathon is a joined event between EAL/tech event and PROSA.

Go [here](https://www.prosa.dk/kalender/hele-kalenderen/?tx_moccrmintegration_courses[course]=1220&tx_moccrmintegration_courses[action]=show&tx_moccrmintegration_courses[controller]=Course&cHash=2e8d96451a4df67abc4d564bf648a187) for info and signup.
