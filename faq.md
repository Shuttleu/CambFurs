---
layout: default
title: FAQ
---
# FAQ

You can find a list of commonly asked questions below

{% for item in site.data.faq %}
- [{{ item.question }}](#faq{{forloop.index}})
{% endfor %}

{% for item in site.data.faq %}
## {{ item.question }} {#faq{{forloop.index}}}
- {{ item.answer }}
{% endfor %}