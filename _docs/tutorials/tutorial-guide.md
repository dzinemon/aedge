---
layout: docs-item

atitle: Tutorial Guide 
subtitle: Tutorial Guide awesome subtitle

category: tutorials
icon: icon-Helmet-1
math: true
---

# Overview Markdown content `goes` here
## Overview Markdown content `goes` here

When \\( $a \ne 0$\\), there are two solutions to \\(ax^2 + bx + c = 0 \\) and they are $$x = {-b \pm \sqrt{b^2-4ac} \over 2a}.$$

### Overview Markdown content `goes` here

{% highlight ruby %}
require 'redcarpet'
markdown = Redcarpet.new("Hello World!")
puts markdown.to_html
{% endhighlight %}