---
layout: page
eventpath: "hackathon_2016_may"
eventname: "Hackathon May 2016"
other_files:
- techEvent Folder singlePage.pdf
- techEvent Folder singlePage.pub
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

