# [AlphaEdge website](https://alphaedge.io) project

https://alphaedge.io

Branches:
* master
* ae-dev

### Jekyll part

Clone/fork the project

Install Jekyll - [Quick start](https://jekyllrb.com/docs/quickstart/)

run
```
bundle install
```
```
jekyll serve
```

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