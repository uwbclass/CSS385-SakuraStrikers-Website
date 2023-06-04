---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: header-start.png
widget1:
  title: "About Our Game"
  url: 'https://uwbclass.github.io/CSS385-SakuraStrikers-Website/our-game/'
  image: widget-1-302x182.png
  text: 'Check out screenshots and the trailer of our game, as well as where to play it!'
widget2:
  title: "Documentation & Deliverables"
  url: 'https://uwbclass.github.io/CSS385-SakuraStrikers-Website/documentation/'
  image: widget-2-302x182.png
  text: 'Check under the hood to see how everything runs and what we created for CSS 385!'
widget3:
  title: "About Team JOGM"
  url: 'https://uwbclass.github.io/CSS385-SakuraStrikers-Website/info/'
  image: widget-github-303x182.png
  text: 'Who, what, where, why, and how is a JOGM (yog-em)? Meet the team and course!'
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
  url: https://iproxypi.github.io/CSS385_Project/WebGLBuild4/
  text: Play Sakura Strikers here ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
