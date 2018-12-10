---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    image_fullwidth: IMG_3937.jpg
    background-color: "#262930"
    caption: Plön, Germany
widget1:
  title: <i class="fas fa-heart wow bounceIn text-primary"></i> Mutualism
#  url: 'http://phlow.github.io/feeling-responsive/blog/'
#  image:
  text: 'How mutualisms are initiated and what keeps them from breaking down?'
widget2:
  title:   <i class="fas fa fa-paw wow bounceIn text-primary" data-wow-delay=".1s"></i> Antagonism
#  url: 'http://phlow.github.io/feeling-responsive/info/'
  text: 'Host-pathogen co-evolution, antibiotic resistance and classical predator prey dynamics'
#  video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""/></a>'
widget3:
  title:   <i class="fas fa-gamepad wow bounceIn text-primary" data-wow-delay=".2s"></i> Game dynamics
#  url: 'https://github.com/Phlow/feeling-responsive'
#  image: IMG_8120.jpg #widget-github-303x182.jpg
  text: 'via evolutionary game theory and theoretical ecology, a trove of mathematical tools.'
widget4:
  title:   <i class="fas fa-venus-mars wow bounceIn text-primary" data-wow-delay=".3s"></i> PopGen
#  url: 'https://github.com/Phlow/feeling-responsive'
#  image: IMG_8120.jpg #widget-github-303x182.jpg
  text: 'Focusing on the knowledge transfer between <em>EGT</em> and <em>Population Genetics</em>!'


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
  url: /changelog/
  text: Latest News! ›
  style: success
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

<link rel="stylesheet" href="https://use.fontawesome.com/releases/v5.5.0/css/all.css" integrity="sha384-B4dIYHKNBt8Bc12p+WXckhzcICo0wtJAoU8YZTY5qE0Id1GSseTk6S+L3BlXeVIU" crossorigin="anonymous">


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
