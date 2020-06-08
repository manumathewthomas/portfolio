---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Learning Patterns in Sample Distributions for Monte Carlo Variance Reduction"
summary: "We visualize and learn the shapes of statistical sample distributions in Monte Carlo rendering, and apply that knowledge to produce denoised images from small sample sets."
authors: []
tags: []
categories: []
date: 2020-06-07T23:34:50-07:00

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

url_code: ""
url_pdf: "https://arxiv.org/abs/1906.00124"
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---
This paper investigates a novel a-posteriori variance reduction approach in Monte Carlo image synthesis. Unlike most established methods based on lateral filtering in the image space, our proposition is to produce the best possible estimate for each pixel separately, from all the samples drawn for it. To enable this, we systematically study the per-pixel sample distributions for diverse scene configurations. Noting that these are too complex to be characterized by standard statistical distributions (e.g. Gaussians), we identify patterns recurring in them and exploit those for training a variance-reduction model based on neural nets. In result, we obtain numerically better estimates compared to simple averaging of samples. This method is compatible with existing image-space denoising methods, as the improved estimates of our model can be used for further processing. We conclude by discussing how the proposed model could in future be extended for fully progressive rendering with constant memory footprint and scene-sensitive output.
