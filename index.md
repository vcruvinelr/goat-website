---
width: full
alert:
  content: "[Help us to improve GOAT by participating in this survey](https://www.umfrage.sv.bgu.tum.de/index.php/837925?lang=en)"
navbar:
  sticky: true
  # scroll_up: true
  animation: true
  # transparent: true
  # transparent_color: light
header:
  layout: 1-1 # Options: left, center, 1-1, 1-2, 1-3 or 2-3
  background_image: normal_isochrone.png
  background_overlay: "rgba(255, 255, 255, 0.15)"
  heading_size: large
  header_size: large
  parallax: true
  container: small
  content:
    block: home-header-2
    title: false
---

{% include cards.html 
  block="feature" 
  section_background="default" 
  section_size="large"
  section_content_align="center"
  media="top"
  grid="1-3"
  gutter="large"
  icon_color="#19B037"
%}

{% include cards.html 
  block="goat-1" 
  media="right" 
  section_size="large"
  section_background="muted"
%}

{% include cards.html 
  block="goat-2" 
  media="left" 
  section_size="large"
  section_padding_remove="top"
  section_background="muted"
%}

{% include cards.html 
  block="goat-3" 
  media="right" 
  section_size="large"
  section_padding_remove="top"
  section_background="muted"
%}