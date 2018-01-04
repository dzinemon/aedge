# [AlphaEdge website](https://alphaedge.io) project

https://alphaedge.io

Branches:
* master
* ae-dev

---

## Jekyll part

Clone/fork the project

Install Jekyll - [Quick start](https://jekyllrb.com/docs/quickstart/)

run `bundle install` & `jekyll serve`

### Mathjax-in-markdown

Use the MathJax delimiters to start and end each formula as follows:

* For centered formulae, use `\\[` and `\\]`.
* For inline formulae, use `\\(` and `\\)`.

source - This [blog post](https://hiltmon.com/blog/2017/01/28/mathjax-in-markdown/)

add `math: true` to front-matter to add Mathjax Script to the page

### Highlight with Rouge

`{% highlight python %}
x = ('a', 1, False)
{% endhighlight %}`


### Add lightbox feature to image in Markdown

use `{: data-lightbox="true"}`

```markdown
[![Alt text](http://via.placeholder.com/900x400)](http://via.placeholder.com/1800x800){: data-lightbox="true"}
```

source - This [blog post](https://kramdown.gettalong.org/quickref.html)

---

### Collections and posts

1. Trading Software Solutions
   - Live Trading
   - Portfolio management
   - Portfolio Backtest
   - Risk Analysis
2. Trading Strategies
   - Mean Reversion
     - Mean Variance Optimizer
   - Portfolio optimisation
   - Momentum
     - Protective Asset momentum
   - Technical analysis
   - Volatility
3. Docs
   - User Guide
   - Developer Guide
   - Framework API
   - Tutorials
4. Support
   - Community Forum
   - Contact Support
5. Blog
   - Posts (blog/post-title)
  
---

### Spacing

set class for spacing of the proper item in `_data/spacing.yml`
```
spacing-class: space--sm, space--lg etc.
page-title-spacing-class: space--sm
sidebar-spacing: '' - no class, boxed--sm, boxed--lg etc.
```