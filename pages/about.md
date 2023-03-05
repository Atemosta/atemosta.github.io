---
layout: page-fullwidth
title: "About"
subheadline: "In this world, a single blade can take you anywhere you want to go"
teaser: "Atemosta is a a group of content creators, engineers, and dreamers who have united their talents to bring us all together. Through the skills we have mastered and the hobbies we are passionate about, we want to try to give something back..."
permalink: "/about/"
header:
    image_fullwidth: z_old/header_about_1600x300.jpg
---

<div class="row">
  <div class="large-6 columns">
      <img src="/images/z_old/about_img1_raw.jpg">
  </div>
  <div class="large-6 columns">
      <img src="/images/z_old/about_img2_raw.jpg">
  </div>
</div>

...and learn at the same time.

A self-styled gamers' guild calling itself a metaverse startup, **Atemosta** wants to bring into reality all the things you love about the virtual world, *especially* community, one project at a time.

## The Team
{% for author in site.data.about %}
  <h3>{{ author.name }}</h3>
  <img src="{{ author.avi }}" alt="{{ author.name }}" /><br>
  <p>
    <b>Role</b>: {{ author.role }} <br/>
    <b>Favorite Anime</b>: {{ author.anime }} <br/>
    <b>Twitter <img src="/images/icon/Twitter_Social_Icon_Circle_Color.png" alt="{{ author.twitter }}" height="20" width="20" /></b>:
        <a href="{{ author.twitter_url }}">{{ author.twitter_handle}}</a> 
      <br/>
  </p>
{% endfor %}
