---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
title: "Maker BBQ"
header:
   image_fullwidth: "coals-banner.png"
widget-1:
    title: "Our Equipment"
    url: "/equipment/"
    text: 'Learn about the Maker BBQ team''s current equipment, and the modifications they have made to improve their gear.'
    image: unsplash_9-302x182.jpg
widget-2:
    title: "Our Team"
    url: '/team/'
    text: 'From those with decades of experience, to those just getting started, our team has one thing in common: A love of BBQ and tinkering.'
    video: '<a href="#" data-reveal-id="videoModal"><img src="http://phlow.github.io/feeling-responsive/images/start-video-feeling-responsive-302x182.jpg" width="302" height="182" alt=""></a>'
widget-3:
    title: "Getting Started"
    url: '/getting-started/'
    text: 'Everyone has to start somewhere, if you''re new to this whole world and wondering where you should start, then this is a good place to begin.'
    image: github-303x182.jpg
---


<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
