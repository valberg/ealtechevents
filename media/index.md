---
layout: page
title: Media
eventmedia:
- techtalks_2017_feb
- techtalks_2017_jan
- techtalks_2016_nov
- gamejam_2016_nov
- techtalks_2016_oct
- techtalks_2016_sep
- gamejam_2016_sep
- hackathon_2016_may
---

* TOC
{:toc}

## Media related to events

{% for ev in page.eventmedia %}
  {% assign event = site.collections | where: "label", {{ev}} | first %}
* [{{ event.type }} - {{ event.date }}]({{ev}})
{% endfor %}

## Other

### Tech event logo

![Tech event logo](techevent_logo_tr.png)

### Tech event banner

![Tech event banner](techevent_banner_tr.png)


### Gamejam logo

![Gamejam logo](gamejam_logo_small.png)
![Gamejam logo (big)](gamejam_logo_big.png)

### EAL logo

![EAL logoxx](eal-logo.svg)
