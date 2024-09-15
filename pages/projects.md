---
layout: list
collection: "projects"
title: Portfolio
description: "Eine Übersicht über unsere Arbeit und Projekte."
permalink: "/projects/"
header_transparent: true

hero:
  enabled: true
  heading: "Portfolio"
  sub_heading: "Unser Arbeits- und Projektportfolio."
  text_color: "#FFFFFF"
  background_color: false
  background_gradient: true
  background_image: "/assets/images/gen/home/home-2-large.webp"
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
  collection: "projects"
  sort_by: "weight" # "date", "weight"
  columns: 2
  prevent_click: false
outro:
  enabled: true
  align: left
  image: false
  heading: "Haben Sie weitere Fragen?"
  buttons:
    enabled: true
    list:
      - text: "Kontakt aufnehmen"
        url: "/contact"
        external: false
        fa_icon: false
        size: "normal"
        outline: false
        style: "primary"
---
