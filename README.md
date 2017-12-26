<ul>
{% for preset in site.data.presets %}
  <li>
    <a>
      {{ preset.creator }}
    </a>
  </li>
{% endfor %}
</ul>
