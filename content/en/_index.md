---
title: Showcase
type: landing

sections:

  - block: slider
    weight: 1
    content: 
      slides:
        - title: "👋 Hi, I'm Dae-bok Lee"
          content: "A sophomore game designer who loves creating worlds players can truly live in."
          align: center
          background:
            image:
              filename: slide1.jpg
              filters:
                brightness: 0.6
                opacity: 0.5
            position: center
            color: '#222'
            overlay:
              color: '#000000'   
              opacity: 0.6
        - title: "🎮 Designing emotional gameplay"
          content: "I believe games should make players *feel* — not just play."
          align: center
          background:
            image:
              filename: slide2.jpg
              filters:
                brightness: 0.6
                opacity: 0.5
            position: center
            color: '#222'
            overlay:
              color: '#000000'   
              opacity: 0.6
        - title: "📂 Explore My Portfolio"
          content:  |
            Check out the projects and designs I've created so far.<br>
            <a href="/about/" class="blox-btn blox-btn-primary">View About</a>
          align: center
          background:
            image:
              filename: slide3.jpg
              filters:
                brightness: 0.6
                opacity: 0.5
            position: center
            color: '#222' 
            overlay:
              color: '#000000'   
              opacity: 0.6
          link:
          icon: graduation-cap
          icon_pack: fas
          text: View about
          url: ../about/




    design:
      is_fullscreen: false
      slide_height: "480px"
      loop: true
      interval: 3500
      transition: fade

  # - block: markdown
  #   weight: 10
  #   headless: false
  #   content:
  #     title:
  #     subtitle:
  #     text: |
  #       <br> <span style="font-size:130%">👋 Hi, I'm **Dae-bok Lee**— a sophomore at Jeonbuk <br>National University, aspiring to become a game designer.  
  #       I love creating worlds where players can step in as <br>characters and explore their own stories.
  #       {style="font-size: 1.2rem; color: #FFB76B;"}
  #       Check out my [About](/about/) and portfolio below 😍
  #       <br>
  #   design:
  #     columns: '1'
  #     align: center
  #     css_class: tight-spacing text-center
      
  - block: portfolio
    weight: 20
    headless: false
    active: true
    title: "My Projects"
    subtitle: "Explore my portfolio"
    content:
      page_type: project
      filter_default: 0
      filter_button:
        - name: All
          tag: '*'
        - name: Machine Learning
          tag: ML
        - name: Computer Vision
          tag: CV
        - name: NLP
          tag: NLP
    design:
      columns: '1'
      view: masonry
      flip_alt_rows: false
      max_width: '1200px'
      background:
        color: '#000'
        overlay:
          color: '#000000'
          opacity: 0.4
      spacing:
        padding: [20, 20, 20, 20]


---
