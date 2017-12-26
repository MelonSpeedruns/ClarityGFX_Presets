<ul>
{% for preset in site.data.presets %}
  <h1>{{ preset.name }}</h1>
<h2>Created by: {{ preset.creator }}</h2>
  <a>{{ preset.description }}</a>
  </br>
    <img src="{{ preset.screenshot1 }}"/>
    <img src="{{ preset.screenshot2 }}"/>
    <img src="{{ preset.screenshot3 }}"/>
    <img src="{{ preset.screenshot4 }}"/>
    <img src="{{ preset.screenshot5 }}"/>
{% endfor %}
</ul>
