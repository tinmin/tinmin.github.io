---
layout: default
title: Store
head: header.html
---
<button class="snipcart-checkout">Click here to checkout</button>
<span class="snipcart-items-count"></span>
<span class="snipcart-total-price"></span>

{% include header.html %}
<main class="main">
<div class="products">
{{ content }}
</div>
</main>
{% include footer.html %}

[back](./)
