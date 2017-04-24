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

Go [here](https://www.prosa.dk/kalender/hele-kalenderen/?tx_moccrmintegration_courses[course]=1220&tx_moccrmintegration_courses[action]=show&tx_moccrmintegration_courses[controller]=Course&cHash=2e8d96451a4df67abc4d564bf648a187) for info and signup.


Venue
----------

{% include venue.html %}

We meet in room B2.48

The door will be open in the daytime, and students will have all-time access using their tokens or student cards. We will arrange for a phone number to call, if the door is locked.

Please note that the windows must be kept closed throughout the weeked. This is an alarm thing, and the guards don't like to be called unneccesarily.


Transportation and parking (!)
------------

{% include transportation.html %}

Media
---------

We have logos and posters [here]({{ site.baseurl }}/media).
