<ul>
{% for preset in site.data.presets %}
  <h1>{{ preset.name }}</h1>
<h2>Created by: {{ preset.creator }}</h2>
  <a>{{ preset.description }}</a>
{% endfor %}
</ul>
