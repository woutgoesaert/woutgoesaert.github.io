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

{% assign science_talks = site.talks | where: "type", "science" | sort: "date" | reverse %}
{% assign outreach_upcoming = site.talks | where: "type", "outreach" | where: "upcoming", true | sort: "date" %}
{% assign outreach_past = site.talks | where: "type", "outreach" | where: "upcoming", false | sort: "date" | reverse %}

<h2>Science talks</h2>
<ul>
  {% for talk in science_talks %}
  <li>
    <strong>{{ talk.date | date: "%B %Y" }}</strong> &mdash; {{ talk.title }}, {{ talk.event }}{% if talk.location %}, {{ talk.location }}{% endif %}{% if talk.link %} (<a href="{{ talk.link }}">details</a>){% endif %}
  </li>
  {% endfor %}
</ul>

<h2>Outreach talks</h2>

{% if outreach_upcoming.size > 0 %}
<h3>upcoming</h3>
<ul>
  {% for talk in outreach_upcoming %}
  <li>
    <strong>{{ talk.date | date: "%B %Y" }}</strong> &mdash; {{ talk.title }}, {{ talk.event }}{% if talk.location %}, {{ talk.location }}{% endif %}{% if talk.link %} (<a href="{{ talk.link }}">details</a>){% endif %}
  </li>
  {% endfor %}
</ul>
{% endif %}

<h3>past</h3>
<ul>
  {% for talk in outreach_past %}
  <li>
    <strong>{{ talk.date | date: "%B %Y" }}</strong> &mdash; {{ talk.title }}, {{ talk.event }}{% if talk.location %}, {{ talk.location }}{% endif %}{% if talk.link %} (<a href="{{ talk.link }}">details</a>){% endif %}
  </li>
  {% endfor %}
</ul>
