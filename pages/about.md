---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

Hi I am **{{ site.author.name }}** :wave:,<br>
I am a recent college graduate from the University of North Carolina at Chapel Hill where I studied Statistics, Computer Science, and Economics. I hail from Boulder, CO and in my spare time I enjoy hiking and playing badminton. I'm also an avid fan of hockey, and have worked on various hockey projects as seen in my projects page. 

<div class="row">
{% include about/skills.html title="Programming Skills" source=site.data.programming-skills %}
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>

<div class="row">
{% include about/timeline.html %}
</div>
