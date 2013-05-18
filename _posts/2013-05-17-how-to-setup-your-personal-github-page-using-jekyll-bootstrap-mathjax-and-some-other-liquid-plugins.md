---
layout: post
title: "How to setup your personal GitHub page using Jekyll, Bootstrap, MathJax, and some other Liquid plugins"
shorttitle: "How to setup your personal GitHub page"
tagline: "using Jekyll, Bootstrap, MathJax, and some other Liquid plugins"
category: tips
tags: [jekyll, bootstrap, mathjax]

---
{% include JB/setup %}

Disclaimer: this is not a complete guide, I've just taken notes for myself in case I will need to repeat the process again.

## Facts, My Reasoning
- Students, researchers, etc. need **a personal website** to list their publications, provide additional information on those.
- I have [one](http://www.cse.ohio-state.edu/~kucuktun/), but I will end up losing it (cf. [personal](http://cs.bilkent.edu.tr/~onurk) [experience](http://web.archive.org/web/20090202061629/http://cs.bilkent.edu.tr/~onurk/)) after I graduate.
- You can register a free [GitHub](http://github.com) account and it provides [GitHub Pages](http://pages.github.com/) for free, including the hosting and static content generation from your entries.

## Setup, test local, push
1. Follow the steps in [http://jekyllbootstrap.com/](http://jekyllbootstrap.com/)
2. After cloning the Jekyll+Bootstrap, read [http://jekyllbootstrap.com/usage/jekyll-quick-start.html](http://jekyllbootstrap.com/usage/jekyll-quick-start.html)
3. Compile files with `$ jekyll build`, start the local server with `$ jekyll -w serve`.
4. Hack theme files, stylesheets, default pages, headers, etc. to your taste.
5. Check questions and answers at [http://stackoverflow.com/questions/tagged/jekyll](http://stackoverflow.com/questions/tagged/jekyll).
6. Find useful Liquid plugins, such as, for [embedding YouTube videos](https://gist.github.com/joelverhagen/1805814) or [displaying equations](https://gist.github.com/drbunsen/2695841) using [MathJax](http://www.mathjax.org/), like:
{% m %} J_\alpha(x) = \sum\limits_{m=0}^\infty \frac{(-1)^m}{m! \, \Gamma(m + \alpha + 1)}{\left({\frac{x}{2}}\right)}^{2 m + \alpha} {% em %}
7. Additional information: [GitHub Pages Help](https://help.github.com/categories/20/articles)

## Result
- This website [onurkucuktunc.github.io](http://onurkucuktunc.github.io)
- or, if I get my own domain name, I can still use the [GitHub Pages](http://pages.github.com/) by [setting up a custom domain with Pages](https://help.github.com/articles/setting-up-a-custom-domain-with-pages).