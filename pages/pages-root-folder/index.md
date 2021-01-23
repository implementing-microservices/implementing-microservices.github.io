---
#
# Use the widgets beneath and the content will be
# inserted automagically in the webpage. To make
# this work, you have to use › layout: frontpage
#
layout: frontpage
header:
    image: "mup-book-cover.png"
    background-color: "##fcfcfc"
    caption_dis: Microservices Up & Running
    caption_url_dis: http://microservicesup.com
widget1:
  title: "Five Guiding Principles"
  url: 'https://implementing-microservices.github.io/five-principles-ms/'
  image: mup-five.jpg
  text: 'The five guiding principles that shaped our microservices design decisions.'
widget2:
  title: "Code Samples"
  url: 'https://github.com/implementing-microservices'
  image: mup-code.jpg
  text: 'Most of the code for the book is under the <i>Implementing Microservices</i> organization on Github. In cases where the book is referring to other repositories, they are linked in the text directly.'
widget3:
  title: "Links to Tools"
  image: mup-tools.jpg
  text: '<ul><li><a href="https://www.terraform.io/">Terraform</a></li>
<li><a href="https://kubernetes.io/">Kubernetes</a></li>
<li><a href="https://helm.sh/docs/topics/charts/">Helm</a></li>
<li><a href="https://traefik.io/traefik-enterprise/">Traefik</a></li>
</ul>
'
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
  url: http://microservicesup.com/
  text: Buy the book ›
permalink: /index.html
#
# This is a nasty hack to make the navigation highlight
# this page as active in the topbar navigation
#
homepage: true
---

