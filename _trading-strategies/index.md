---
layout: strategy

permalink: /trading-strategies/

atitle: "Trading Strategies"
subtitle: "Whether you’re building a welcome mat for your SaaS or a clean, corporate portfolio, Stack has your design needs covered."

title: AlphaEdge Trading Strategies page

description: AlphaEdge | Trading Strategies - Description 160-260 chars

seo:
  type: WebPage

---

## Markdown *content* goes _here_

<div class="row">
  {% assign strategies = site.trading-strategies | sort: "order" %}

  {% for item in strategies %}
  {% if item.name %}
    {% include trading-strategies/category-thumb.html %}
  {% endif %}
  {% endfor %}
</div>
<!--end of row-->
<!--end of container-->
