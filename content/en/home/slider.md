---
widget: slider
headless: true
active: true
weight: 20
title: Showcase

content:
  slides:
  - image: "{{ '/media/slide1.jpg' | relURL }}"
    caption: "🌌 Explore new worlds"
  - image: "{{ '/media/slide2.jpg' | relURL }}"
    caption: "🎮 Design immersive gameplay"
  - image: "{{ '/media/slide3.jpg' | relURL }}"
    caption: "🧭 Craft emotional adventures"


design:
  height: "480px"
  autoplay: true
  interval: 3500
  show_captions: true
  transition: fade
---
