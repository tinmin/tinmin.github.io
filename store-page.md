---
layout: default
---

## store

{% for product in site.products %}
{% include product.html %}
{% endfor %}

{% include header.html %}
 <main class="main">
 <div class="products">
{{ content }}
 </div>
 </main>
 {% include footer.html %}

[back](./)
