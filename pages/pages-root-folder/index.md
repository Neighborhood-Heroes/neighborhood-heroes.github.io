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
  title: "Become a Hero"
  url: 'http://phlow.github.io/feeling-responsive/info/'
  # image: widget-1-302x182.jpg
  text: |
    <p>
      We are looking for partners like you to join our community.
    </p>
    <p>
      Our goal is to support your dreams and to give you the opportunity to support others within our family with your passions.
    </p>
    <p>
      <center>
        <a class="button small radius" href="mailto:BeAHero@neighborhoodhero.es">Share with us</a>
      </center>
    </p>
  showButton: false
widget2:
  title: "Support our Family"
  url: 'http://phlow.github.io/feeling-responsive/blog/'
  # image: widget-1-302x182.jpg
  text: |
    <p>
      Donations to Neighborhood Heroes are allocated to coaching, holding events for the local community, and a scholarship fund to help our heroes achieve their dreams.
    </p>
    <p>
      As a 501(c)(3), any donations to Neighborhood Heroes are tax deductible.
    </p>
    <center>
    <form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
      <input type="hidden" name="cmd" value="_s-xclick">
      <input type="hidden" name="hosted_button_id" value="9APC3TKHJ3QHA">
      <input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donateCC_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
      <img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
    </form>

    </center>
  showButton: false
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