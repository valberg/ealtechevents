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

Nothing specific planned except continued work on the projects


### Sunday


| Time  | Comment |
| ------------- | ------------- |
| 14:00 -  | Expo of projects and/or prototypes created |


## Proposed projects

### China VPN (Morten)

I want to set up a network that may be used to connect using VPN from china. 

It must be secured and we want to see what th great firewall of china is doing when you connect. In order to do that, we need a plan, some intrusion detection, loggin, and whatnot.

I will probably do most of it using ansible.
