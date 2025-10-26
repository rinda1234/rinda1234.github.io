---
title: 쇼케이스
type: landing

sections:

  - block: slider
    weight: 1
    content: 
      slides:
        - title: "👋 안녕하세요, 저는 이대복입니다"
          content: "플레이어가 실제로 몰입할 수 있는 세계를 만드는 것을 목표로 하는 전북대학교 컴퓨터인고지능학과 2학년 학생입니다."
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
        - title: "🎮 감성적인 게임플레이 디자인"
          content: "게임은 단순히 플레이하는 것이 아니라 플레이어가 몰입해야 한다고 생각합니다."
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
        - title: "📂 포트폴리오 살펴보기"
          content: "저의 정보를 살펴보세요."
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
            text: 정보 보기
            url: ../about/
            class: "custom-btn"

    design:
      is_fullscreen: false
      slide_height: "480px"
      loop: true
      interval: 3500
      transition: fade

  - block: portfolio
    weight: 20
    headless: false
    active: true
    title: "내 프로젝트"
    subtitle: "프로젝트를 확인해보세요"
    content:
      page_type: project
      filter_default: 0
      filter_button:
        - name: 전체
          tag: '*'
        - name: 머신러닝
          tag: ML
        - name: 컴퓨터 비전
          tag: CV
        - name: 자연어 처리
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
