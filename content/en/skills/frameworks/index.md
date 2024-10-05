---
# Page title
title: Frameworks
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
      title: Programming Languages
      subtitle: I have experience with Flask and Vue.js.

  - block: slider
    content:
      slides:
        - title: Flask
          content: I have experience in creating a course registration schedule planning web app using the Flask framework. Flask is a Python-based web framework that allows you to develop lightweight and fast web applications. I mainly used it to build backend APIs and connect them to the frontend through HTML templates.
          align: center
          background:
            image:
              filename: flask.png
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: Vue.js
          content: I have experience in creating a simple toy project using the Vue.js framework. Vue is useful for creating reactive web applications, and its component-based development method makes it easy to maintain. I focused on immediately reflecting user input in the front-end.
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
