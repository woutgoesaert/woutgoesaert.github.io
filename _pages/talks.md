---
layout: page
permalink: /talks/
title: talks
description: A list of past and upcoming talks and presentations.
nav: true
nav_order: 3
---

<p>
  For speaking inquiries, please get in touch by email:
  <a href="mailto:goesaert@strw.leidenuniv.nl">goesaert@strw.leidenuniv.nl</a>.
</p>

{% assign upcoming_talks = site.talks | where: "upcoming", true | sort: "date" %}
{% assign past_talks = site.talks | where: "upcoming", false | sort: "date" | reverse %}

{% if upcoming_talks.size > 0 %}
<h2>Upcoming</h2>
<ul>
  {% for talk in upcoming_talks %}
  <li>
    <strong>{{ talk.date | date: "%B %Y" }}</strong> &mdash; {{ talk.title }}, {{ talk.event }}{% if talk.location %}, {{ talk.location }}{% endif %}{% if talk.link %} (<a href="{{ talk.link }}">details</a>){% endif %}
  </li>
  {% endfor %}
</ul>
{% endif %}

<h2>Past</h2>
<ul>
  {% for talk in past_talks %}
  <li>
    <strong>{{ talk.date | date: "%B %Y" }}</strong> &mdash; {{ talk.title }}, {{ talk.event }}{% if talk.location %}, {{ talk.location }}{% endif %}{% if talk.link %} (<a href="{{ talk.link }}">details</a>){% endif %}
  </li>
  {% endfor %}
</ul>
