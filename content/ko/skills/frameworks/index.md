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
        - title: <span style="font-size:80%">Flask</span>
          content: <span style="font-size:80%">Flask 프레임워크를 이용해 수강신청시간표 계획 웹앱을 제작한 경험이 있습니다.</span>
          align: center
          background:
            image:
              filename: flask.jpg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: <span style="font-size:80%">Vue.js</span>
          content: <span style="font-size:80%">Vue.js 프레임워크를 이용해 간단한 토이 프로젝트를 제작한 경험이 있습니다.</span>
          align: center
          background:
            image:
              filename: Vue.png
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
