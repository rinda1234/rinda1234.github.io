---
title: Showcase
type: landing

sections:

  - block: slider
    weight: 1
    content:
      slides:
        - title: "🌌 Explore new worlds"
          align: center
          background:
            image:
              filename: slide1.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#222'
        - title: "🎮 Design immersive gameplay"
          align: center
          background:
            image:
              filename: slide2.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#222'
        - title: "🧭 Craft emotional adventures"
          align: center
          background:
            image:
              filename: slide3.jpg
              filters:
                brightness: 0.6
            position: center
            color: '#222' 


    design:
      is_fullscreen: false
      slide_height: "480px"
      loop: true
      interval: 3500
      transition: fade

  - block: markdown
    weight: 10
    headless: false
    content:
      title:
      subtitle:
      text: |
        👋 Hi, I'm **Dae-bok Lee**— a sophomore at Jeonbuk <br>National University, aspiring to become a game designer.  
        I love creating worlds where players can step in as <br>characters and explore their own stories.
        {style="font-size: 1.2rem; color: #FFB76B;"}
        Check out my [About](/about/) and portfolio below 😍
    design:
      columns: '1'
      align: center
      css_class: tight-spacing
      
  - block: collection
    content:
      filters:
        folder: home
      count: 10
    design:
      columns: 1


---
