---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Manumorph"
summary: "Deep Painterly Harmonization is an extension of style transfer, but includes a content object which is placed on the style image. The network then harmonizes the style and the content. "
authors: []
tags: []
categories: []
date: 2020-06-08T01:10:46-07:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: "https://github.com/sarahmfrost/manumorph"
url_pdf: "https://github.com/sarahmfrost/manumorph/blob/master/Manumorph.pdf"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
Style transfer, the technique by which the style of one image is applied to the content of another, is one of the most popular and well-known uses of neural network algorithms. Deep Painterly Harmonization is an extension of style transfer, but includes a content object which is placed on the style image. The network then harmonizes the style and the content. We build on Deep Painterly Harmonization, originally implemented in Torch, and re-implement the paper in Tensorflow. We extend the uses of the algorithm to explore different categories of visual media modification. We discuss the ramifications of style harmonization and style transfer on societal concepts of art, and we compare the results of the Tensorflow and Torch algorithms. Finally, we propose a design for a web application that will allow casual creators to create new art using the algorithm, without a strong technical background.