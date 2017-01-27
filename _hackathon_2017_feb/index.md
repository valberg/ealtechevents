---
layout: page
title: Introduction
---

{% assign path_elements = page.url | split: "/"  %}
{% assign eventname = path_elements[1] %}
{% assign event = site.collections | where: "label", eventname | first %}

{{ event.title }}
---------------------------------

This is the page where we will collect relevant information related to the hackathon.


What is this?
---------------

Build IT days is an event in which computer programmers and others involved in software development, including graphic designers, interface designers and project managers, collaborate intensively on software projects.

We will find interesting people and projects, who will pitch their ideas. The idea is then "vote with our feet" to join the most interesting project, and create a working prototype by Sunday. See the [schedule page]({{site.baseurl}}/{{eventname}}/schedule.html) for a brief description of the projects. Feel free to come with your own idea and pith it!

No coding, artist or other skills are required. Just your willingness to help

Make friends over small projects and have a fun time.


What's in it for me?
-----------------------

* Meet like minded people that you don't see everyday
* Get cred for your cool project
* Break mental walls, and get inspired
* Learn something new

Who should come?
--------------------

* Everybody with an interest in IT and want to built something with others
* Programmers, electronics devs, sys­admins, networkadmins, senior/junior/newbies


I want to come, now what?
-----------------------------

Go to the registration page to [sign up]({{site.baseurl}}/{{eventname}}/sign_up.html)


Bootnotes
--------------

In the coming weeks, we will continuously update the content to reflect any changes.

If you have any questions, please [send an email](mailto:{{ site.email }}) or write to us on facebook
