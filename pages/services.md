---
layout: list
collection: "Services"
title: Unsere Dienstleistungen
description: "Unsere Dienstleistungen"
permalink: "/unsere-dienstleistungen/"
header_transparent: true

hero:
  enabled: true
  heading: "Unsere Dienstleistungen"
  sub_heading: "Wir bieten folgende Dienstleistungen und mehr an:"
  text_color: "#FFFFFF"
  background_color: false
  background_gradient: true
  background_image: "/assets/images/gen/home/home-8-large.webp"
  background_image_blend_mode: overlay # "overlay", "multiply", "screen"
  fullscreen_mobile: false
  fullscreen_desktop: false
  height: "500px"
  buttons:
    enabled: false
    list:
      - text: "Kontakt aufnehmen"
        url: "/contact"
        external: false
        fa_icon: false
        size: large
        outline: true
        style: "light"

grid:
  collection: "services"
  sort_by: "weight" # "date", "weight"
  columns: 3
  prevent_click: false

intro:
  enabled: false
  align: left
  image: false
  heading: "A Full Service Agency"
  sub_heading: "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut eget sapien in elit semper accumsan. Pellentesque accumsan ut tortor eu varius. Sed id tincidunt massa, ut egestas orci."
  buttons:
    enabled: false
    list:
      - text: "Über uns"
        url: "/about/"
        external: false
        fa_icon: false
        size: normal

outro:
  enabled: true
  align: left
  image: false
  heading: "Haben Sie noch Fragen?"
  sub_heading: "Buchen Sie eine individuelle Beratung!"
  buttons:
    enabled: true
    list:
      - text: "Termin vereinbaren"
        url: "/contact"
        external: false
        fa_icon: false
        size: normal
---
