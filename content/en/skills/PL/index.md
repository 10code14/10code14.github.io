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
      title: Programming Languages
      subtitle: I have experience with Python, JavaScript, and SQL.

  - block: slider
    content:
      slides:
        - title: Python
          content: I have experience developing backends with the Flask framework using Python. Python's simplicity and extensibility have helped me quickly create prototypes or solve complex problems using various libraries.
          align: center
          background:
            image:
              filename: Python.png
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: JavaScript
          content: I have experience with the Vue.js framework using JavaScript. JavaScript is a language that is very suitable for controlling the client-side behavior of web applications and responding to user interactions, and with Vue, I focused on implementing interactive UI.
          align: center
          background:
            image:
              filename: javascript.jpeg
              filters:
                brightness: 0.2
            position: center
            color: "#000"

        - title: SQL
          content: I have experience managing system data using SQL queries via MYSQL. I focused on performing fast data retrieval and management through database design and optimization, and extracting and analyzing data from multiple tables using complex queries.
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
