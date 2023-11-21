---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
  image_fullwidth: "final-website.jpg"
#"paul-cézanne-kaartspelers.jpg"
  #caption: Paul Cézanne
  #caption_url: "https://commons.wikimedia.org/wiki/File:Les_Joueurs_de_cartes,_par_Paul_C%C3%A9zanne.jpg" 
widget1:
  title: "Een mooi produkt"
  url: '/duurzame-kaarten/'
  text: 'Prachtige kaartspellen van duurzaam materiaal.'
widget2:
  title: "Speciale edities"
  url: '/kaartspellen/'
  text: 'Nog een origineel cadeautje nodig voor de feestdagen?'
widget3:
  title: "Relatiegeschenken"
  url: '/kaartspellen/relatiegeschenken/'
  text: 'Wij maken graag een kaartspel op maat, als relatiegeschenk.'
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
  url: /contact/
  text: Neem contact op voor meer informatie ›
  style: alert
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---
