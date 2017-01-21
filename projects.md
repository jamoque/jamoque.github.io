---
layout: no_sidebar
title: Projects
permalink: /projects/
---
<style type="text/css">
	#main {
		width:100%;
		margin: 0;
		margin: auto;
		margin-top: 2em;
		padding: 0;
	}

	#wrapper {
		width: 100%;
		margin: 0;
		padding: 0;
	}

	ul {
		padding-left: 0em;
	}

	ul li {
		padding: 0;
	}

	.mini-post {
		width: 31%;
		display: inline-block;
		text-decoration: none;
		margin: 0 0.5em 1em 0.5em;
	}

	@media screen and (max-width: 878px) {

			#main {
				border: 0px solid red;
			}

			.mini-post {
				width: 95%;
			}
	}

</style>

<div style="width: 96%; margin-right: 2%; margin-left: 2%;">
	<ul>
		{% for post in site.data.projects.projects %}
			<li class="mini-post">
				{% if post.featureimg %}
				<a href="{{ post.url | prepend: site.baseurl }}" class="image"><img src="{{ post.featureimg | prepend: site.baseurl }}"></a>
				{% endif %}
				<header>
					<h3><a href="{{ post.url | prepend: site.baseurl }}">{{ post.title }}</a></h3>
					<time class="published" datetime="{{ post.date | date: "%Y-%m-%d" }}">{{ post.date | date: "%d %B, %Y" }}</time>
				</header>
			</li>
		{% endfor %}
	</ul>
</div>