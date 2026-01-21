- [Home](index.md)

{% assign pages_sorted = site.pages | sort: "title" %}
{% assign parents = "" %}

{% for page in pages_sorted %}
  {% if page.title and page.url != "/" and page.url != "/index.html" and page.url != "/privacy.html" %}
    {% assign segments = page.url | split:'/' %}
    {% assign depth = segments.size | minus: 2 %}

    {% if depth == 0 %}
- [{{ page.title }}]({{ page.url }})
    {% else %}
      {% assign parent_folder = segments[segments.size-2] %}
      {% unless parents contains parent_folder %}
- {{ parent_folder | capitalize }}
  {% assign parents = parents | append: parent_folder | append: "," %}
      {% endunless %}
  - [{{ page.title }}]({{ page.url }})
    {% endif %}
  {% endif %}
{% endfor %}

- [Privacy Policy](privacy.md)
