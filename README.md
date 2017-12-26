<ul>
{% for preset in site.data.presets %}
  <h1>{{ preset.name }}</h1>
<h3>Created by: {{ preset.creator }}</h3>
  <a>{{ preset.description }}</a>
  <br>
  <br>
    <img src="{{ preset.screenshot }}"/>
{% endfor %}
</ul>
