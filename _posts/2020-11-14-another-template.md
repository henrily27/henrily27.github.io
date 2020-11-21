---
layout: splash
title: "Test Post"
date: 2020-11-14
tags: [something, test]
header:
  overlay_color: "#000"
  overlay_filter: 0.5
  overlay_image: /images/train.jpg
  actions:
    - label: "Download"
      url: "https://github.com/mmistakes/minimal-mistakes/"
  caption: "Photo credit: [**Unsplash**](https://www.unsplash.com)"
excerpt: >
  *Write something*<br />
  <small>-- write something else</small>

feature_row_left:
  - image_path: /images/airport.jpg
    title: "Image on the left"
    excerpt: "This is the image placed on the **left**."
    url: https://www.google.com/
    btn_class: "btn--primary"
    btn_label: "Learn more"

feature_row_right:
  - image_path: /images/hotel.jpg
    title: "Image on the right"
    excerpt: "This is the image placed on the **right**."
    url: https://www.google.com/
    btn_class: "btn--primary"
    btn_label: "Learn more"

feature_row_center:
  - image_path: /images/ai2.jpg
    title: "Image in the center"
    excerpt: "This is the image placed in the **center**."
    url: https://www.google.com/
    btn_class: "btn--primary"
    btn_label: "Learn more"

feature_row:
  - image_path: /images/airport.jpg
    title: "Image 1"
    excerpt: "First Image"
  - image_path: /images/hotel.jpg
    title: "Image 2"
    excerpt: "Second Image"
    url: "https://www.google.com/"
    btn_class: "btn--primary"
    btn_label: "Learn more"
  - image_path: /images/train.jpg
    title: "Image 3"
    excerpt: "Third Image"
    url: "https://www.google.com/"
    btn_class: "btn--primary"
    btn_label: "Learn more"


mathjax: "true"
---

Table of Content (manually)
- [Image Placed on the Left](#image-place-on-the-left)
- [Ways to insert images](#ways-to-insert-images)
  - [Size as is](#size-as-is)
  - [Adjust image size](#adjust-image-size)


# Image placed on the Left
{% include feature_row id="feature_row_left" type="left" %}

# Image placed on the Right
{% include feature_row id="feature_row_right" type="right" %}

# Image placed on the Center
{% include feature_row id="feature_row_center" type="center" %}

# Three Images side by side
{% include feature_row %}

# Ways to insert images
## Size as is
<img src="{{ site.url }}{{ site.baseurl }}/images/train.jpg" alt="tree">

## Adjust image size
<div style="width:20%; font-size:80%; text-align:center;">
<img src="/images/train.jpg" style="padding-bottom:0.5em;"/>
</div> 


