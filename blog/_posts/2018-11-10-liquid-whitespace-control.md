---
layout: post
title: 'TIL: Liquid WhiteSpace Control'
date: 2018-11-10 20:31 -0500
tags: til, jekyll

categories:  article
---
Did a quick view source and saw this on the new theme:

![Original image with whitespace present](/assets/images/posts/whitespace/original.png)

Although it has no net effect on the page (maybe a couple kb saved) it was nice to find these Liquid docs on [controlling white space](https://shopify.github.io/liquid/basics/whitespace/).

> In Liquid, you can include a hyphen in your tag syntax {% raw %}{{-, -}}, {%-, and -%}{% endraw %} to strip whitespace from the left or right side of a rendered tag.

Now, with a couple find and replaces we end up with:

![Updated image with whitespace removed](/assets/images/posts/whitespace/updated.png)
