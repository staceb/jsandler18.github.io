# Test for index update

## Tutorial
{% assign items = site.tutorial | sort: 'title' %}
{% for item in items %}
[{{item.title}}]({{item.url}})
{% endfor %}
## Extra Information
{% assign itemss = site.extra | sort: 'title' %}
{% for item in itemss %}
[{{item.title}}]({{item.url}})
{% endfor %}


