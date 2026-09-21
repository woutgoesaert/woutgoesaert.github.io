---
layout: about
title: about
permalink: /
subtitle: "PhD Candidate, Leiden Observatory" # TODO: double-check/edit this line

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: >
    <p>Wout M. Goesaert</p>
    <p>(he/him)</p>

selected_papers: false # research section is written directly into this page below instead
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

Hi there! I am a PhD candidate at Leiden University, supervised by [Prof. Mariska Kriek](https://home.strw.leidenuniv.nl/~kriek/). I work in observational extragalactic astrophysics, where I study how asymptotic giant branch stars shape the light, composition, and evolution of their host galaxies.

**A little bit about myself**

I grew up in the beautiful town of Genk, Belgium. My passion for astronomy began early, when I joined a youth astronomy organization called JVS-Descartes at a local public observatory. In 2019, I moved to the Netherlands to study astronomy and physics in Leiden. For my master's project, I studied how supermassive black holes are fed, which took me all the way to Chile. Since September 2025, I've been working on my PhD in Leiden.

I enjoy giving public talks, writing popular science articles and looking at the world from weird angles through my camera. But whenever I'm not distracted by our universe, I also enjoy playing volleyball, cooking and listening to my vinyl records.

<div class="row align-items-start mt-4">
  <div class="col-12 order-2 order-md-1 col-md-5 mb-4 mb-md-0">
    <img src="/assets/img/cw_leonis.jpg" class="img-fluid rounded z-depth-1" alt="Hubble image of the carbon-rich TP-AGB star CW Leonis">
    <p class="text-center mt-2"><em>Expanding shells of dust fly out from the surface of the carbon-rich TP-AGB star CW Leonis - Credit: ESA/Hubble, NASA.</em></p>
  </div>
  <div class="col-12 order-1 order-md-2 col-md-7">
    <p><strong>My research</strong></p>
    <p>My PhD focuses on a rather peculiar type of star: thermally pulsing asymptotic giant branch (TP-AGB) stars. You can think of them as cosmic dust factories, that enrich the universe with dust and with elements crucial for life, such as carbon and nitrogen. Dust is the building material from which planets are eventually made. Our own blue marble, Earth, formed largely from dust that was produced in the bubbling atmospheres of TP-AGB stars. Without them, life on our planet would likely look very different, if it existed at all.</p>
    <p>Yet despite their importance, the evolution of TP-AGB stars, their dust production, and their contribution to the light of galaxies like our own Milky Way remain a mystery in many ways. They're among the least understood of all stellar types. These uncertainties also ripple outward to other fundamental questions in astronomy. For example, it significantly complicates the measurements of ages and masses of galaxies in the universe. That is why I study them, and why I'm currently tackling questions like:</p>
    <ul>
      <li>How much light do AGB stars produce?</li>
      <li>What is their role in the production of dust in the universe?</li>
      <li>And how can we unlock the NIR to learn about their molecular absorption features?</li>
    </ul>
  </div>
</div>

<div class="row justify-content-center mt-5">
  <div class="col-sm-10">
    <img src="/assets/img/alma_fieldwork.jpg" class="img-fluid rounded z-depth-1" alt="Wout at the ALMA Observatory in the Atacama Desert, Chile">
    <p class="text-center mt-2"><em>At the ALMA Observatory in the Atacama Desert, Chile.</em></p>
  </div>
</div>

## Exceptional Ordinary Physics

<p class="text-muted">My monthly popular science column, where I dig into the extraordinary physics hiding behind everyday things. Read it <a href="/blog/">here</a>.</p>

## Research

<div class="publications" markdown="1">

#### First-author publications

{% bibliography --group_by none --query @*[firstauthor=true]* %}

#### Other publications

{% bibliography --group_by none --query @*[firstauthor=false]* %}

</div>
