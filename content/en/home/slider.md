---
widget: slider
headless: true
active: true
weight: 20
title: Showcase

content:
  slides:
    - image: "{{ $slide1 := resources.Get \"media/slide1.jpg\" | images.Fit \"1200x600\" }}{{ $slide1.RelPermalink }}"
      caption: "🌌 Explore new worlds"
    - image: "{{ $slide2 := resources.Get \"media/slide2.jpg\" | images.Fit \"1200x600\" }}{{ $slide2.RelPermalink }}"
      caption: "🎮 Design immersive gameplay"
    - image: "{{ $slide3 := resources.Get \"media/slide3.jpg\" | images.Fit \"1200x600\" }}{{ $slide3.RelPermalink }}"
      caption: "🧭 Craft emotional adventures"

design:
  height: "480px"
  autoplay: true
  interval: 3500
  show_captions: true
  transition: fade
---
