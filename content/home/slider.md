---
widget: slider
widget_id: slider
headless: true
weight: 10
active: true
design:
  columns: "1"
  background:
    text_color_light: false
    image_darken: 0
    image_position: center

# Slide interval.
# Use `false` to disable animation or enter a time in ms, e.g. `5000` (5s).
interval: 3000

# Minimum slide height.
# Specify a height to ensure a consistent height for each slide.
height: 500px

item:
  - title: ""
    content: ""
    # Choose `center`, `left`, or `right` alignment.
    align: center
    # Overlay a color or image (optional).
    #   Deactivate an option by commenting out the line, prefixing it with `#`.
    overlay_color: ''  # An HTML color value.
    overlay_img: Workshop-Python-2018.jpg  # Image path relative to your `assets/media/` folder
    overlay_filter: 0.5  # Darken the image. Value in range 0-1.
    # Call to action button (optional).
    #   Activate the button by specifying a URL and button label below.
    #   Deactivate by commenting out parameters, prefixing lines with `#`.
    cta_label: ""
    cta_url: ""
    #cta_icon_pack: fas
    #cta_icon: graduation-cap
  - title: Left
    content: 'I am left aligned 😄'
    align: left
    overlay_color: '#555'
    overlay_img: ''
    overlay_filter: 0.5
  - title: Right
    content: 'I am right aligned 😄'
    align: right
    overlay_color: '#333'
    overlay_img: ''
    overlay_filter: 0.5
---
