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
      {style="color: red"}
      text: <span style="font-size:80%">name:이승협</span>
      design:
        background:
          # Choose a color such as from https://html-color-codes.info
          color: "#F2F2F2"
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  - block: features
    content:
      title:
      text: <br><span style="font-size:125%">test</span>

  - block: markdown
    id: section-2
    content:
      title: Section 2
      subtitle: A subtitle
      text: Add your Section 2 content here...
  - block: markdown
    id: section-3
    content:
      title: Section 3
      subtitle: A subtitle
      text: Add your Section 3 content here...
---
