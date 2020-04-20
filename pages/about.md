---
layout: page-fullwidth
title: "About"
subheadline: "In this world, a single blade can take you anywhere you want to go"
teaser: "Since years I am programming and designing websites. I love to work with open source tools and learn via code from others. This time I want to try to give something back..."
permalink: "/about/"
header:
    image_fullwidth: "header_about_1600x300.jpg"
---

<div class="row">
  <div class="large-6 columns">
      <img src="{{site.url}}/images/about_img1_raw.jpg">
  </div>
  <div class="large-6 columns">
      <img src="{{site.url}}/images/about_img2_raw.jpg">
  </div>
</div>



...and learn at the same time.

*Feeling Responsive* is my first theme which I let into the world. It's built on work and knowledge of others. While I am still designing it, you read about whats behind this theme in the – *hopefully* – near future.

## The Team
{% for author in site.data.about %}
  <h3>{{ author.name }}</h3>
  <img src="{{ site.url }}/{{ author.avi }}" alt="{{ author.name }}" />
  <p>Here is a quick intro</p>
  <img src="{{ site.url }}/images/icon/Twitter_Social_Icon_Circle_Color.png" alt="{{ author.twitter }}" height="20" width="20" />
  <a href="{{ author.twitter_url }}">{{ author.twitter_handle}}</a>

<!-- <img src="{{site.url}}/images/about_img1_raw.jpg"> -->
{% endfor %}

<!-- <img src="{{site.url}}/images/about_img1_raw.jpg"> -->
