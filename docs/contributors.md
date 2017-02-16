---
layout: page
navigation_title: Contributors
title: Contributors
permalink: /contributors/
button: true
cover: 'https://mozillatn.github.io/clubs/assets/mozilla-tn-bannerc.png'
---

Here are the list of amazing Mozilla contributors from our club.

<h3>Present Contributors</h3>
<div class="contributors_wrapper">
{% for contributor in site.data.present_contributors %}
<div class="contributors">

<div class="pic" style="height: 130px; width: 130px">
<img src="https://www.gravatar.com/avatar/bc550139be48cb8ce92c0d4933f73b9c?s=256"></div><br>
<p class="name">Name: Lokeshwaran.A</p>
<p class="contribution">Contribution Area: Webvr</p>
</div>

<div class="pic" style="height: 130px; width: 130px">
<img src="https://www.gravatar.com/avatar/bc550139be48cb8ce92c0d4933f73b9c?s=256"></div><br>
<p class="name">Name: Manoj Anbarasu</p>
<p class="contribution">Contribution Area: Addons</p>
</div>

<div class="pic" style="height: 130px; width: 130px">
<img src="https://www.gravatar.com/avatar/479088660d4d1f7057b382bd5cd47930?s=256"></div><br>
<p class="name">Name: Manoj Kumar TL</p>
<p class="contribution">Contribution Area: Addons</p>
</div>


{% endfor %}
</div>
<h3>Past Contributors</h3>
<div class="contributors_wrapper">
{% for contributor in site.data.past_contributors %}
<div class="contributors">

<div class="pic" style="height: 130px; width: 130px">

<img src="{{ contributor.photo }}"></div><br>

<p class="name">Name: {{ contributor.name }}</p>
<p class="contribution">Contribution Area:{{ contributor.contribution }}</p>

</div>
{% endfor %}
</div>
