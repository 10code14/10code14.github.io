---
# Page title
title: Frameworks & Tools
# Page type - we want a landing page (such as a homepage)
type: landing

banner:
  image: "framework.jpg"
  caption: "Image credit: [**Geo**](https://github.com/gcushen/)"

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: Frameworks & Tools
      subtitle: 프레임워크로는 Flask, Vue.js를 사용한 경험이 있습니다.

  - block: slider
    content:
      slides:
        - title: Flask
          content: Flask 프레임워크를 이용해 수강신청 시간표 계획 웹앱을 제작한 경험이 있습니다. Flask는 파이썬 기반의 웹 프레임워크로, 가볍고 빠르게 웹 애플리케이션을 개발할 수 있습니다. 주로 백엔드 API를 구축하고, HTML 템플릿을 통해 프론트엔드와 연동하는 방식으로 활용했습니다.
          align: center
          background:
            image:
              filename: flask.png
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: Vue.js
          content: Vue.js 프레임워크를 이용해 간단한 토이 프로젝트를 제작한 경험이 있습니다. Vue는 반응형 웹 애플리케이션 제작에 유용하며, 컴포넌트 기반 개발 방식 덕분에 유지보수가 용이합니다. 프론트엔드 부분에서 사용자의 입력을 즉각적으로 반영하는 데 중점을 두었습니다.
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
