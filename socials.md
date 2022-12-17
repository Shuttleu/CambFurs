---
layout: default
title: Socials
---
# Socials

{% for item in site.data.socials %}
[{{ item.site }}]({{ item.address }}){: .chat-link }
{: .link-button}
{% endfor %}