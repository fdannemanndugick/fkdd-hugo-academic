---
widget: slider  # Use the Slider widget as this page section
weight: 1  # Position of this section on the page
active: true  # Publish this section?
headless: true  # This file represents a page section.

design:
  # Slide height is automatic unless you force a specific height (e.g. '400px')
  slide_height: ''
  is_fullscreen: true
  # Automatically transition through slides?
  loop: false
  # Duration of transition between slides (in ms)
  interval: 2000

content:
  slides:
    - title: Recent fieldwork in New Mexico
      content: 
      align: center
      background:
        position: right
        color: '#666'
        brightness: 0.7
        media: array.jpg
        fit: cover
    - title: 
      content: 'Share your knowledge with the group and explore exciting new topics together!'
      align: left
      background:
        position: center
        color: '#555'
        brightness: 0.7
        media: van.jpg
        fit: cover
    - title: ROSES Meetup at AGU
      content: At the 2021 AGU, former ROSES instructors and students met for the first time in person!
      align: right
      background:
        position: center
        color: '#333'
        brightness: 0.5
        media: roses.jpg
        fit: cover
---