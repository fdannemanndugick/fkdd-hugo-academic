---
# SLIDER for PHOTOS
widget: slider
headless: true  # This file represents a page section.
weight: 120

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 5000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
# This is a hack to put more CSS into the bg image
height: '300px; background-position:center; background-repeat: no-repeat; background-size: cover'




item:
# carousel_chalkboard

  - title: Vince Van
    content: 'SNL Geophysics Field Van'
    # Choose `center`, `left`, or `right` alignment.
    align: right
    # overlay_color: '#666'  # An HTML color value.
    overlay_img: fkdd-photos/van.jpg  # path relative to `assets/media/` folder
    overlay_filter: 1  # Darken the image. Value in range 0-1.
    # THIS DOESN'T WORK (6/7/21); just modify images
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: 
    cta_url: 
    cta_icon_pack: 
    cta_icon: 
    credit: ''

  - title: Aliens
    content: 'Fieldwork in Roswell, NM'
    # Choose `center`, `left`, or `right` alignment.
    align: left
    # overlay_color: '#666'  # An HTML color value.
    overlay_img: fkdd-photos/aliens.jpg  # path relative to `assets/media/` folder
    overlay_filter: 1  # Darken the image. Value in range 0-1.
    # THIS DOESN'T WORK (6/7/21); just modify images
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: 
    cta_url:
    cta_icon_pack: 
    cta_icon: 
    credit: ''

---
