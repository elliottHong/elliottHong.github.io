---
layout: page
title: About
permalink: /about/
weight: 3
---

# **About Me**

<h4>Hi, I am <strong>{{ site.author.name }},</strong></h4>
<p></p>
I am junior at DigiPen Institute of Technology.

<h2 class="mb-3">Skills</h2>
<div class="row">
<div class="col-md-6">
{% include about/cards.html title="Programming Skills" source=site.data.programming-skills %}
</div>
<div class="col-md-6">
{% include about/skills.html title="Other Skills" source=site.data.other-skills %}
</div>
<div class="w-100"></div>
<div class="col mt-4">
{% include about/cards.html title="Tools / API" source=site.data.toolsAPI %}
</div>
</div>

<div class="row">
{% include about/timeline.html title="Experience" source=site.data.timeline %}
</div>