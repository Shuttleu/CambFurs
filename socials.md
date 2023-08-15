---
layout: default
title: Socials
---
# Socials

<div class="row">
{% for item in site.data.socials %}
<div class="col-12 col-lg link-button">
<a href="{{ item.address }}" class="chat-link">
<svg xmlns="http://www.w3.org/2000/svg" x="0px" y="0px" width="48" height="48" viewBox="0 0 48 48">
{% for icon_path in item.icon %}
<path fill="{{ icon_path.colour }}" d="{{ icon_path.path }}"></path>
{% endfor %}
</svg>
</a>
</div>
{% endfor %}
</div>