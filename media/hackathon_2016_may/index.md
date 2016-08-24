---
layout: page
eventpath: "hackathon_2016_may"
eventname: "Hackathon May 2016"
talks_files:
- Artificial Intelligence - talk.pdf
- eal-hackathon-pass-management-victor-truica.pdf
- Git_101 2016.pdf
- OpenStack.pdf
- security and privacy.pdf
- tools.pdf
other_files:
- logo1.png
- poster1.jpg
- poster1.pdf
title: Media
---

Media related to {{ page.eventname }}
-----------------------

{% if page.talks_files %}
talks:

{% for mfile in page.talks_files %}
* [{{mfile}}]({{mfile }})
{% endfor %}
{% endif %}


{% if page.other_files %}
other:

{% for mfile in page.other_files %}
* [{{mfile}}]({{mfile }})
{% endfor %}
{% endif %}

