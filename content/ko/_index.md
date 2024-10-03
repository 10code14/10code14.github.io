---
# Page title
title: 시작 화면
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: <span style="font-size:80%">Seunghyeop-Lee,<br>Department of Computer Engineering,<br>Jeonbuk National University</span>
      subtitle: 전북대학교 컴퓨터공학부 학사 과정을 밟고 있는 이승협의 개인 사이트입니다.
      text:
      design:
        background:
          # Choose a color such as from https://html-color-codes.info
          color: "navy"
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  - block: hero
    content:
      title: 이승협
      image:
        # Reference an image in your `assets/media/` folder
        filename: test.png

      # Add your Hero text here
      text: |-
        <span style="font-size:80%">소속: 전북대학교(2019 ~)<br>관심분야: IT 인프라 / 유지보수<br>전공: 컴퓨터공학부(2019 ~)</span>
    design:
      # Choose an optional background color, gradient, image, or video
      background:

  - block: slider
    content:
      slides:
        - title: <span style="font-size:70%">Recruit</span>
          content: <span style="font-size:70%">Interested in MacsLAB?</span>
          align: center
          background:
            image:
              filename: test.png
              filters:
                brightness: 0.4
            position: center
            color: "#000"
          link:
            icon: user
            icon_pack: fas
            text: <span style="font-size:60%">Join Us</span>
            text-color: "#000"
            url: contact

        - title: <span style="font-size:70%">AI</span>
          content: <span style="font-size:70%">의료/항공우주/컨텐츠 등 특성화 분야에 적용 가능한 AI 기술 개발<span style="font-size:70%">
          align: center
          background:
            image:
              filename: test.png
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Healthcare</span>
          content: <span style="font-size:70%">의료 및 헬스케어 분야에 적용 가능한 AI 기술 개발</span>
          align: center
          background:
            image:
              filename: test.png
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Mathematics</span>
          content: <span style="font-size:70%">AI와 관련된 수학 및 최적화 이론 연구</span>
          align: center
          background:
            image:
              filename: test.png
              filters:
                brightness: 0.4
            position: center
            color: "#000"

        - title: <span style="font-size:70%">Development</span>
          content: <span style="font-size:70%">기반 기술을 활용한 Full-Stack 어플리케이션 개발</span>
          align: center
          background:
            image:
              filename: test.png
              filters:
                brightness: 0.4
            position: center
            color: "#000"

    design:
      # Slide height is automatic unless you force a specific height (e.g. '400px')
      slide_height: "700px"
      slide_width: "100px"
      is_fullscreen: false
      # Automatically transition through slides?
      loop: true
      # Duration of transition between slides (in ms)
      interval: 3000
---
