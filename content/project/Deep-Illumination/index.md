---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep Illumination"
summary: "A novel machine learning technique for approximating global illumination (GI) in real-time applications using a Conditional Generative Adversarial Network."
authors: [Manu Mathew Thomas, Angus Forbes]
tags: []
categories: []
date: 2020-06-07T23:08:22-07:00

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

url_code: "https://github.com/CreativeCodingLab/DeepIllumination"
url_pdf: "https://arxiv.org/pdf/1710.09834.pdf"
url_slides: ""
url_video: "https://www.youtube.com/watch?v=z_zmRWxU-PY&t=228s"

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


We present Deep Illumination, a novel machine learning technique for approximating global illumination (GI) in real-time
applications using a Conditional Generative Adversarial Network. Our primary focus is on generating indirect illumination and
soft shadows with offline rendering quality at interactive rates. Inspired from recent advancement in image-to-image translation
problems using deep generative convolutional networks, we introduce a variant of this network that learns a mapping from Gbuffers (depth map, normal map, and diffuse map) and direct illumination to any global illumination solution. Our primary
contribution is showing that a generative model can be used to learn a density estimation from screen space buffers to an
advanced illumination model for a 3D environment. Once trained, our network can approximate global illumination for scene
configurations it has never encountered before within the environment it was trained on. We evaluate Deep Illumination through
a comparison with both a state of the art real-time GI technique (VXGI) and an offline rendering GI technique (path tracing). We
show that our method produces effective GI approximations and is also computationally cheaper than existing GI techniques.
Our technique has the potential to replace existing precomputed and screen-space techniques for producing global illumination
effects in dynamic scenes with physically-based rendering quality.