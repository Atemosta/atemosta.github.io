---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "A Tempest of Stars"
header:
  image_fullwidth: header_atos.jpg
widget1:
  title: "Immria"
  url: 'http://localhost:4000/projects/immria/'
  image: widget-vr-302x182.jpg
  text: 'Be remembered forever in the metaverse.'
widget2:
  title: "Blog"
  url: 'https://atemosta.com/blog'
  image: widget-tutorials-302x182.jpg
  text: 'Catch up on the latest project updates and announcements.'
widget3:
  title: "Contact"
  url: 'https://atemosta.com/contact'
  image: widget-apps-302x182.jpg
  text: 'Product support and collaboration requests.'
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
# Use the call for action to show a button on the frontpage
#
# To make internal links, just use a permalink like this
# url: /getting-started/
#
# To style the button in different colors, use no value
# to use the main color or success, alert or secondary.
# To change colors see sass/_01_settings_colors.scss
#
callforaction:
  url: https://tinyletter.com/Atemosta
  text: 📧 Join our monthly newsletter ›
  style: alert
permalink: /index.html
homepage: true
---
