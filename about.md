---
Title: About
description: We've built an amazing team of developers, marketers, designers and sales people.
image: ![image](https://unsplash.com/photos/ai-generated-portrait-of-a-model-with-polka-dot-shirt-pF8mmOdb1KI)
---

<section class="hero" style="background-image: url({% include relative-src.html src=page.image %})">
	<div class="inner-hero text-container">
		<div class="hero-text-container">
			<h1 class="editable">You ABSOLUTE cutie <3</h1>
			<p class="subtext editable"> We are totally nuts about cashews and wanted to tell you how eating a small portion of nuts or another form of protein before eating your meal can prevent blood sugar spikes. </p>
		</div>
	</div>
</section>

<section class="pad">
	<div class="container">
		<p class="editor-link"><a href="cloudcannon:collections/_staff_members" class="btn"><strong>&#9998;</strong> Tell Jurgen he is cute</a></p>
		<ul class="staff">
			{% for person in site.staff_members %}
				<li>
					<div class="square-image" style="background-image: url({% include relative-src.html src=person.image_path %})"></div>
					<div class="name"><a target="_blank" href="https://twitter.com/{{ person.twitter_username }}">{{ person.name }}</a></div>
					<div class="position">{{ person.position }}</div>
				</li>
			{% endfor %}
		</ul>
	</div>
</section>
