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
    id: aboutme
    content:
      image: /static/test.png # 프로필 사진 경로
      title: eunghyeop Lee
      subtitle: Department of Computer Engineering, Jeonbuk National University
      text: 학부 과정 동안 여러 프로젝트와 연구를 통해 프로그래밍 실력을 쌓았습니다. GitHub 및 LinkedIn을 통해 더 많은 정보를 확인해보세요.
      cta:
        - cta_text: GitHub
          cta_link: https://github.com/your-github-id
        - cta_text: LinkedIn
          cta_link: https://linkedin.com/in/your-linkedin-id

  - block: markdown
    id: section-3
    content:
      title: Section 3
      subtitle: A subtitle
      text: Add your Section 3 content here...
---
