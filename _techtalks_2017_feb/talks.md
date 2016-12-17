---
layout: page
title: Talks
---

* TOC
{:toc}

{% assign path_elements = page.url | split: "/"  %}
{% assign eventname = path_elements[1] %}
{% assign event = site.collections | where: "label", eventname | first %}

We do not publish presenters email adresses, so any questions to the presenters should be directed to [the organisers](mailto:{{ site.email }}) and we will forward your questions.

## Schedule for Thursday {{ event.date }}

{% include talks_schedule.html %}

{% assign talks = (event.docs | where: "layout", "talk" | sort: "time") %}
{% for talk in talks %}
  {% if talk.description %}
## {{talk.title }} ({{talk.presenter}})
{{ talk.description }}

  {% endif %}
{% endfor %}
