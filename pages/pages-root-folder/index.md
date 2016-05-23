---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: head.jpg
widget1:
  title: "What is the Mobile Fablab?"
  url: 'http://mobile.fablabsaigon.org/the-project/'
  image: event.jpg
  text: 'Our mission is innovation literacy in Vietnam. Especially, we want to show kids’ throughout Vietnam that digital fabrication can help make their dreams come true.'
widget2:
  title: "Our Journey Through Vietnam"
  url: 'http://mobile.fablabsaigon.org/the-journey/'
  image: map.JPG
  text: 'Ho Chi Minh city, Danang and Hanoi are all big cities. Our mission is innovation literacy and we want to reach out to smaller cities in Vietnam.
  <br/>'
widget3:
  title: "<br/>Who are we?"
  url: 'http://mobile.fablabsaigon.org/who-we-are/'
  image: logofablab.png
  text: 'Fablab Saigon started in March 2014. A Fablab is a small-scale workshop offering (personal) digital fabrication.
  <br/>
  <br/>'
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

permalink: /index.html
---
<div id="videoModal" class="reveal-modal large" data-reveal="">
  <div class="flex-video widescreen vimeo" style="display: block;">
    <iframe width="1280" height="720" src="https://www.youtube.com/embed/3b5zCFSmVvU" frameborder="0" allowfullscreen></iframe>
  </div>
  <a class="close-reveal-modal">&#215;</a>
</div>
