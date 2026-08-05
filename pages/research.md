# Research

My research examines how people interpret and respond to information in technology-mediated environments.

{% for item in site.research %}

## [{{ item.title }}]({{ item.url | relative_url }})

{{ item.description }}

{% endfor %}
