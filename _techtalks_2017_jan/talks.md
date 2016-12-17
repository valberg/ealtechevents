---
layout: page
title: Talks
eventpath: techtalks_2017_jan
---

* TOC
{:toc}

{% assign event = site.collections | where: "label", page.eventpath | first %}

We do not publish presenters email adresses, so any questions to the presenters should be directed to [the organisers](mailto:{{ site.email }}) and we will forward your questions.

{% assign talks = (event.docs | where: "layout", "talk" | sort: "time") %}


## Schedule for Thursday {{ event.date }}

{% include talks_schedule.html %}

{% for talk in talks %}
  {% if talk.description %}
## {{talk.title }} ({{talk.presenter}})
{{ talk.description }}

  {% endif %}
{% endfor %}
