---
layout: post
title: "My Markdown Cheet"
index_title: "Markdown Sheet for this site"
tags: [markdown, test]
---

<aside class="warning">
<strong>Warning</strong>
</aside>

## Table of Content

1. [Code](#code)
2. [Some Topics](#some-topics-io)


## Some topics I/O

Sawas dee pre mai :) Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim similique magni minus hic saepe fuga ratione doloribus tempore, provident, autem repudiandae nulla dolore esse odit ducimus numquam quam porro quibusdam?
<aside>
<strong>2019 Laew</strong>
</aside>

<img src="/static/markdown-sheet/test-img-center.jpg" class="centered shadowed" />

Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim similique magni minus hic saepe fuga ratione doloribus tempore, provident, autem repudiandae nulla dolore esse odit ducimus numquam quam porro quibusdam?

## Code

{% highlight rust %}
// Bind a value to an owner:
let owner = value;

// Create a new scope and borrow the value from the owner:
{
    let borrow = owner;

    // Owner has no access to the value now.
    // But the borrower can read and modify the value:
    borrow.mutate();

    // And then return the borrowed value to the owner:
    owner = borrow;
}
{% endhighlight %}

## Quote

    Some Quote lel~


## Floating Image

QEWRTYY<sup>[[1]](#ref1)</sup> Lorem ipsum.

<!-- <img src="/static/markdown-sheet/test-img-center.jpg" class=float-left" /> -->
<img src="/static/markdown-sheet/test-img-center.jpg" class="float-left shadowed" />

Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim similique magni minus hic saepe fuga ratione doloribus tempore, provident, autem repudiandae nulla dolore esse odit ducimus numquam quam porro quibusdam?

Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim similique magni minus hic saepe fuga ratione doloribus tempore, provident, autem repudiandae nulla dolore esse odit ducimus numquam quam porro quibusdam?

Lorem ipsum dolor sit amet consectetur adipisicing elit. Enim similique magni minus hic saepe fuga ratione doloribus tempore, provident, autem repudiandae nulla dolore esse odit ducimus numquam quam porro quibusdam?

## Reference

<a name="ref1"></a>
<small>[1]</small> Qwerty Layout [Wiki](https://en.wikipedia.org/wiki/QWERTY) &nbsp;[&uarr;](javascript:history.back())
