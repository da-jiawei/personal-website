---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: markdown

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 66

title: Gallery
subtitle:

design:
  columns: '1'

gallery_item:
- album: <demo>
  image: <IMAGE 1 NAME>.jpg
  caption: Write your image 1 caption here
- album: <demo>
  image: <IMAGE 2 NAME>.jpg
  caption: Write your image 2 caption here

---

{{< gallery album="demo" >}}
