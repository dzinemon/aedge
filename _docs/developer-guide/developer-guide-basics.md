---
layout: docs-item

atitle: Developer Guide basics
subtitle: Developer Guide basics - Guide awesome subtitle

title: AlphaEdge Developer Guide basics page

description: AlphaEdge | Developer Guide basics page - Description 160-260 chars

seo:
  type: WebPage

category: developer-guide
icon: icon-Helmet-3
math: true
---

# Overview Markdown content `goes` here
## Overview Markdown content `goes` here

---

When \\( $a \ne 0$\\), there are two solutions to \\(ax^2 + bx + c = 0 \\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

### Overview Markdown content `goes` here

{% highlight ruby %}
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
{% endhighlight %}