---
layout: default
---

{% for repository in site.github.public_repositories %}
-   [{{ repository.name }}]({{ repository.name | absolute_url }}) - {{ repository.description }}
{% endfor %}
