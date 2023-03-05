---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "A Tempest of Stars"
header:
  image_fullwidth: z_old/header_atos.jpg
widget1:
  title: "Projects"
  url: 'http://atemosta.com/projects/'
  image: z_old/widget-vr-302x182.jpg
  text: 'What are we up to?'
widget2:
  title: "Contact"
  url: 'https://atemosta.com/contact'
  image: z_old/widget-apps-302x182.jpg
  text: 'Get in touch with us!'
widget3:
  title: "Donate"
  url: 'https://atemosta.com/donate'
  image: z_old/widget-tutorials-302x182.jpg
  text: 'Support our work and get digital rewards!'
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
