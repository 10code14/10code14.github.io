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
      title: <p style="font-size:80%">SeunghyeopLee,<br>Department of Computer Engineering,<br>Jeonbuk National University</p>
      subtitle: 전북대학교 컴퓨터공학부 학사 과정을 밟고 있는 이승협의 개인 사이트입니다.
      text: Add any **markdown** formatted content here - text, images, videos, galleries - and even HTML code!

      widget: hero
      headless: true # This file represents a page section.

      # Put Your Section Options Here (title, background, etc.) ...
      title: My Hero
      weight: 10 # Position of section on the page

      # Hero image (optional). Enter filename of an image in the assets/media/ folder.
      hero_media: ""

      # Call to action links (optional).
      #   Display link(s) by specifying a URL and label below. Icon is optional for `cta`.
      #   Remove a link/note by deleting a cta/note block.
      cta:
        url: "https://wowchemy.com"
        label: Get Started
        icon_pack: fas
        icon: download
      cta_alt:
        url: "https://wowchemy.com"
        label: View Documentation

      # Note. An optional note to show underneath the links.
      cta_note:
        label: ""

# Choose an optional background color, gradient, image, or video
design:
  background:
    gradient_end: "#1976d2"
    gradient_start: "#004ba0"
    text_color_light: true
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
