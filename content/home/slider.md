---
widget: slider
weight: 1
active: true
headless: true

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: true  # false
  # Duration of transition between slides (in ms)
  interval: 9000

# https://emojipedia.org/food-drink/

content:
  slides:
    - title: 👋 PyKale
      content: A library built upon PyTorch for multimodal learning and transfer learning from multiple data sources
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.5
        media: pykale_logo.jpg
      link:
        icon: github
        icon_pack: fab
        text: Explore Now
        url: https://github.com/pykale/pykale
    - title: 🥬 KaleCancer
      content: 'An interactive, plain-language guide to what our multimodal head & neck cancer toolkit can do today'
      align: right
      background:
        position: center
        color: '#0b3d24'
        brightness: 0.6
        media: kalecancer_ml.png
      link:
        icon: stethoscope
        icon_pack: fas
        text: Explore KaleCancer
        url: /cancer/
    - title: Accessible software 🗝️
      content: 'Make abundant machine learning software accessible for interdisciplinary research'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.4
        media: accessible_ml.jpg
      link:
        icon: chalkboard
        icon_pack: fas
        text: Try Colab Tutorial
        url: https://colab.research.google.com/github/pykale/pykale/blob/main/examples/digits_dann_lightn/tutorial.ipynb
    - title: ♻️ Green machine learning
      content: Reduce repetitions, reuse resources, and recycle models to build PyKale
      align: center
      background:
        position: center
        color: '#666'
        brightness: 0.5
        media: green_ml.jpg
      link:
        icon: laptop-code
        icon_pack: fas
        text: Browse Examples
        url: https://github.com/pykale/pykale/tree/main/examples
    - title: Pipeline-based API ⛓️
      content: 'Standardize all machine learning workflows into six steps'
      align: center
      background:
        position: center
        color: '#333'
        brightness: 0.3
        media: pipeline_api.jpg
      link:
        icon: book
        icon_pack: fas
        text: View API Docs
        url: https://pykale.readthedocs.io/en/latest/index.html
---
