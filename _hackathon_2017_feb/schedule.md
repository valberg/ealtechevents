---
layout: page
title: Schedule
---

{% assign path_elements = page.url | split: "/"  %}
{% assign eventname = path_elements[1] %}
{% assign event = site.collections | where: "label", eventname | first %}

* TOC
{:toc}

## Schedule

The event is scheduled for the weekend {{ event.date }}


### Friday

| Time  | Comment |
| ------------- | ------------- |
| 17:30 | We open and orders pizzas  |
| 18:00  | Official start with pitches  |


### Saturday

Nothing specific planned except continued work on the games


### Sunday


| Time  | Comment |
| ------------- | ------------- |
| 14:00 -  | Expo of projects and/or prototypes created |


## Proposed projects

(descriptions to come)
