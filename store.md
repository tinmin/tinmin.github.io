---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: store
---

## each item order contributes $1 donation to charity

{% for product in site.products %}
  {% include product.html %}
{% endfor %}
