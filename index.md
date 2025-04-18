---
title: "Home"
home: true
toc: false
permalink: /index.html
layout: home
seealso: false
hero-image: "/assets/images/banner-grey.png"
hero-alt: "a decorative pattern"
hero-button-text: "hero-button-text"
hero-button-url: "/"
hero-headline: "hero-headline"
---

## h2

### h3

#### h4

Home page content

<p class="annotation">env = {{ jekyll.environment }}</p>

{% include callout.html type="primary" content="callout.html" %}

<p class="annotation">The boxes below only take content as a variable</p>
{% include important.html content="important.html" %}

{% include warning.html content="warning.html" %}

{% include note.html content="note.html" %}

{% include tip.html content="note.html" %}
