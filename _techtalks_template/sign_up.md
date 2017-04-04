---
layout: page
title: About/Sign up
---

{% assign path_elements = page.url | split: "/"  %}
{% assign eventname = path_elements[1] %}
{% assign event = site.collections | where: "label", eventname | first %}



* TOC
{:toc}

To registrer
---------------

{% if event.mailchimp_listid %}
To register, signup here

{% include mailchimp_signup.html listid=event.mailchimp_listid uid=site.mailchimp_uid %}
{% else %}

To register, please [send an email](mailto:{{ site.email }}).

{% endif %}


Time
------------

For the talks go [here](talks.html)

Event
---------

The event is at EAL campus at seebladsgade 1, 5000 Odense C.

<iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2265.3951633205165!2d10.377145315917003!3d55.40345798046134!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x464cdffce26d61f5%3A0xb3c45d391e70236f!2sSeebladsgade+1%2C+5000+Odense+C!5e0!3m2!1sen!2sdk!4v1476866186128" width="600" height="450" frameborder="0" style="border:0" allowfullscreen></iframe>

The event is in the auditorium in building A.


Transportation and parking (!)
------------

{% include transportation.html %}

Food and accomodation
---------------------

There will be cofee and water for the audience.


Media
---------

We have logos and posters [here]({{ site.baseurl }}/media).
