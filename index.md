# Kyopro Encyclopedia of Algorithms and Data Structures (β版)

<dl>
{% for entry in site.entries %}
    {% if entry.draft %}
        <dt>{{ entry.title }} (WIP)</dt>
        <dd>{{ entry.description }}</dd>
    {% else %}
        <dt><a href="{{ site.baseurl }}{{ entry.url }}">{{ entry.title }}</a></dt>
        <dd>{{ entry.description }}</dd>
    {% endif %}
{% endfor %}
</dl>

<div class="github-links">
    <a href="{{ site.github.repository_url }}">GitHub repository</a>
</div>