---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Deep Illumination: Approximating Dynamic Global Illumination with Generative Adversarial Network [2017]"
authors: [Manu Thomas, Angus G Forbes]
date: 2020-06-11T15:35:59-06:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2017-06-11T15:54:16-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: "Arixv"
publication_short: ""

abstract: "We present Deep Illumination, a novel machine learning technique for approximating global illumination (GI) in real-time
applications using a Conditional Generative Adversarial Network. Our primary focus is on generating indirect illumination and
soft shadows with offline rendering quality at interactive rates. Inspired from recent advancement in image-to-image translation
problems using deep generative convolutional networks, we introduce a variant of this network that learns a mapping from Gbuffers (depth map, normal map, and diffuse map) and direct illumination to any global illumination solution. Our primary
contribution is showing that a generative model can be used to learn a density estimation from screen space buffers to an
advanced illumination model for a 3D environment. Once trained, our network can approximate global illumination for scene
configurations it has never encountered before within the environment it was trained on. We evaluate Deep Illumination through
a comparison with both a state of the art real-time GI technique (VXGI) and an offline rendering GI technique (path tracing). We
show that our method produces effective GI approximations and is also computationally cheaper than existing GI techniques.
Our technique has the potential to replace existing precomputed and screen-space techniques for producing global illumination
effects in dynamic scenes with physically-based rendering quality."

# Summary. An optional shortened abstract.
summary: "We present Deep Illumination, a novel machine learning technique for approximating global illumination (GI) in real-time
applications using a Conditional Generative Adversarial Network."

tags: []
categories: []
featured: true

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://arxiv.org/pdf/1710.09834.pdf"
url_code: 
url_dataset:
url_poster:
url_project:
url_slides:
url_source:
url_video: 

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
