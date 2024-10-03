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
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!
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
        <span>소속: 전북대학교(2019 ~)<br>관심사: IT 인프라 / 유지보수<br>전공: 컴퓨터공학부(2019 ~)</span>

        <!--Custom spacing-->
        <div class="mb-3"></div>
        <!--GitHub Button JS-->
        <script async defer src="https://buttons.github.io/buttons.js"></script>
    design:
      # Choose an optional background color, gradient, image, or video
      background:

  - block: markdown
    id: section-3
    content:
      title: Section 3
      subtitle: A subtitle
      text: Add your Section 3 content here...
---
