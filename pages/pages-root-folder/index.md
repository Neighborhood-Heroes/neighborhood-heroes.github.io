---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: NH_jumbotron.jpg
widget1:
  title: "Support our Family"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  image: widget-1-302x182.jpg
  text: 'Emails & stuff'
  showButton: true
widget2:
  title: "Become a Hero"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  image: widget-1-302x182.jpg
  text: 'Partnering stuff'
  showButton: true  
widget3:
  title: '<a class="twitter-timeline" data-height="500" href="https://twitter.com/NeighborHeroes?ref_src=twsrc%5Etfw">Tweets by NeighborHeroes</a> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script>'
  showButton: false
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
  url: https://mailchi.mp/14648d9d0e5e/neighborhood-heroes
  text: Sign up for the Neighborhood Newsletter
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

{% include _bookings.html %}