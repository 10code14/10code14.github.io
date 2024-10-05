---
# Page title
title: Programming Languages
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: slider
    content:
      slides:
        - title: <span style="font-size:80%">Python</span>
          content: <span style="font-size:80%">Python을 이용해 Flask 프레임워크를 다뤄본 경험이 있습니다.</span>
          align: center
          background:
            image:
              filename: Python.png
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: <span style="font-size:80%">JavaScript</span>
          content: <span style="font-size:80%">JavaScript를 이용해 Vue.js 프레임워크를 다뤄본 경험이 있습니다.</span>
          align: center
          background:
            image:
              filename: javascript.jpeg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: '<span style="font-size:80%">SQL</span>'
          content: <span style="font-size:80%">MYSQL을 통해 SQL 쿼리를 이용해 시스템 데이터를 관리한 경험이 있습니다.</span>
          align: center
          background:
            image:
              filename: SQL.png
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
