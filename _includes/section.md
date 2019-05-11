{% assign title = include.title %}
{% assign description = include.description %}
{% assign link = include.link %}
{% assign class = include.class %}
{% assign video = include.video %}
{% assign image = include.image %}


<div class="section">
	<a href="{{link}}">
	{% if video %}
    	<video class="thevideo grayscale{% if class %} {{class}}{% endif %}" muted loop preload="none" 	>
			<source src="{{video}}" type="video/mp4">
    	</video>
    {% else %}
    	<img src="{{image}}" class="grayscale" alt="{{title}}" />
    {% endif %}
 		<div class="overlay">
			<div class="overlay_title">
				{{title}}
			</div>
			<div class="overlay_description">
				{{description}}
			</div>
		</div>
	</a>
</div>

