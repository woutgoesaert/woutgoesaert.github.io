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

Hi there! I am a PhD student at Leiden University. My current research focuses on studying asymptotic giant branch stars in distant quiescent galaxies using NIR observations.

My passion for astronomy began early, prompting me to join a youth astronomy organisation in Belgium, which ultimately inspired my academic career. In 2019, I moved to The Netherlands to study astronomy and physics in Leiden, where I found great joy in physics and astronomy. As part of my master's program, I studied how supermassive black holes are fed, a project which brought me all the way to the Atacama desert in Chile. Now, I am working on my PhD with prof. Mariska Kriek, which is focused on evolved stars in quiescent galaxies.

I enjoy giving talks, writing popular science articles and looking at the world from weird angles through my camera. And whenever I'm not by distracted by our awesome universe, I also enjoy playing volleyball, cooking and listening to my vinyl records.

<div class="row justify-content-center mt-5">
  <div class="col-sm-10">
    <img src="/assets/img/alma_fieldwork.jpg" class="img-fluid rounded z-depth-1" alt="Wout at the ALMA Observatory in the Atacama Desert, Chile">
    <p class="text-center mt-2"><em>At the ALMA Observatory in the Atacama Desert, Chile.</em></p>
  </div>
</div>

## Research

<div class="publications" markdown="1">

#### First-author publications

{% bibliography --group_by none --query @*[firstauthor=true]* %}

#### Other publications

{% bibliography --group_by none --query @*[firstauthor=false]* %}

</div>
