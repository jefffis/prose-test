---
layout: default
---
<div class="center">
	<h1>Visualize Risk
		<span>Create Opportunity</span>
	</h1>
	<p>The risk is unseen threats and lost opportunities. Deploy breakthrough visualization and analytic technologies to blast through sensor overload and turn the most challenging cyber problems into opportunities.</p>
</div>
<img src="http://endgame.com/images/carousel/whiteboard.png" />

<h2>Recent News Items</h2>
<ul>
	{% for post in site.categories.news %}
	<li>
		<a href="{{ site.baseurlsans }}{{ post.url }}">{{ post.title }} <span>{{post.date | date: "%b %Y"}}</span></a>
	</li>
	{% endfor %}
</ul>
<h2>Recent Press Releases</h2>
<ul>
	{% for post in site.categories.press-release %}
	<li>
		<a href="{{ site.baseurlsans }}{{ post.url }}">{{ post.title }} <span>{{post.date | date: "%b %Y"}}</span></a>
	</li>
	{% endfor %}
</ul>