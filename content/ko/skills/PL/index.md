---
# Page title
title: Programming Languages
# Page type - we want a landing page (such as a homepage)
type: landing

# Your landing page sections - add as many different content blocks as you like
sections:
  - block: markdown
    id: section-1
    content:
      title: <span style="font-size:80%">Programming Languages</span>
      subtitle: 프로그래밍 언어로 Python, JavaScript, SQL을 사용한 경험이 있습니다.

  - block: slider
    content:
      slides:
        - title: <span style="font-size:80%">Python</span>
          content: <span style="font-size:80%">Python을 이용해 Flask 프레임워크와 함께 백엔드 개발을 해본 경험이 있습니다. 파이썬은 그 간결함과 확장성 덕분에 빠르게 프로토타입을 제작하거나 다양한 라이브러리를 활용해 복잡한 문제를 해결하는 데 도움이 되었습니다.</span>
          align: center
          background:
            caption: "Image credit: [**Unsplash**](https://unsplash.com/)"
            image:
              filename: Python.png
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: <span style="font-size:80%">JavaScript</span>
          content: <span style="font-size:80%">JavaScript를 이용해 Vue.js 프레임워크를 다뤄본 경험이 있습니다. 자바스크립트는 웹 애플리케이션의 클라이언트 측 동작을 제어하고, 사용자의 상호작용에 반응하는 데 매우 적합한 언어로, Vue와 함께 인터랙티브한 UI를 구현하는 데 중점을 두었습니다.</span>
          align: center
          background:
            image:
              filename: javascript.jpeg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: '<span style="font-size:80%">SQL</span>'
          content: <span style="font-size:80%">MYSQL을 통해 SQL 쿼리를 이용해 시스템 데이터를 관리한 경험이 있습니다. 데이터베이스 설계 및 최적화를 통해 빠른 데이터 검색 및 관리를 수행하며, 복잡한 쿼리를 사용해 여러 테이블에서 데이터를 추출하고 분석하는 데 중점을 두었습니다.</span>
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
