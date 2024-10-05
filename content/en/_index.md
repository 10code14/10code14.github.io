---
# Page title
title: Home
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: Seunghyeop-Lee's portfolio site
      subtitle: This is the personal site of Seunghyeop Lee, who is pursuing a bachelor's degree in computer engineering at Jeonbuk National University.
      text:
      design:
        background:
          # Choose a color such as from https://html-color-codes.info
          color: "navy"
          # Text color (true=light, false=dark, or remove for the dynamic theme color).
          text_color_light: true

  - block: hero
    content:
      title: Seunghyeop Lee
      image:
        # Reference an image in your `assets/media/` folder
        filename: test.png

      # Add your Hero text here
      text: '<span style="font-size:80%">Affiliation: Jeonbuk National University(2019 ~)<br>Areas of Interest: IT Infrastructure / Maintenance<br>Major: Computer Engineering(2019 ~)<br>Career: Member of CPU, programming club(2021~2022)<br></span>'

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
          content: Code Maintenance and Development
          align: center
          background:
            image:
              filename: slider1_code.jpg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: IT Infrastructure
          content: Manages the combination of software, hardware, services and IT resources required to operate and manage an IT environment.
          align: center
          background:
            image:
              filename: slider2.jpg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: Web Development - Front end
          content: Develop a graphical user interface for a website using HTML, CSS, and JavaScript so that users can view and interact with the website.
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
