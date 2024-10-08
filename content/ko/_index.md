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
      title: Seunghyeop-Lee's portfolio site
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
      text: '<span style="font-size:80%">소속: 전북대학교(2019 ~)<br>관심분야: IT 인프라 / 유지보수<br>전공: 컴퓨터공학부(2019 ~)<br>경력 : 프로그래밍 중앙동아리 CPU 소속(2021~2022)<br></span>'

      cta:
        url: "https://github.com/10code14"
        label: GitHub
        icon_pack: fab
        icon: github

      cta_alt:
        url: "/uploads/resume.pdf" # 두 번째 링크의 URL
        label: Resume # 두 번째 버튼에 표시될 텍스트

    design:
      # Choose an optional background color, gradient, image, or video
      background:

  - block: slider
    content:
      slides:
        - title: Code Maintenance and Development
          content: 코드 유지보수 및 개발
          align: center
          background:
            image:
              filename: slider1_code.jpg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: IT Infrastructure
          content: IT 환경을 운영하고 관리하는 데 필요한 소프트웨어, 하드웨어, 서비스 및 IT 자원의 조합을 관리
          align: center
          background:
            image:
              filename: slider2.jpg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: Web Development - Front end
          content: 사용자가 해당 웹 사이트를 보고 상호 작용할 수 있도록 HTML, CSS 및 JavaScript를 사용하여 웹 사이트의 그래픽 사용자 인터페이스를 개발
          align: center
          background:
            image:
              filename: slider3.jpg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

    design:
      slide_height: "700px"
      slide_width: "100px"
      is_fullscreen: false
      loop: true
      interval: 5000
---
