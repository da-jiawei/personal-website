---
# An instance of the Blank widget with a Gallery page element.
# Documentation: https://wowchemy.com/docs/getting-started/page-builder/
widget: markdown

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 60

title: Gallery
subtitle:

design:
  columns: '1'

gallery_item:
- album: demo
  image: Bear lake.jpeg
  caption: Bear Lake at the Rocky Mountain National Park
- album: demo
  image: Lake Estes.jpeg
  caption: Lake Estes with the Rocky Mountain at the back
- album: demo
  image: Mount Bonnell.jpeg
  caption: Overlooking the Texas Colorado river from Mount Bonnell
- album: demo
  image: pedernales falls.jpeg
  caption: Pedernales Falls State Park during the fall
---

{{< gallery album="demo" resize_options="400x300">}}
