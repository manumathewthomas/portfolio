---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "A Reduced-Precision Network for Image Reconstruction [2020]"
authors: [Manu Mathew Thomas, Karthik Vaidyanathan, Gabor Liktor, and Angus G. Forbes]
date: 2020-09-08T15:57:12-05:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-08T15:35:59-07:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["2"]

# Publication name and optional abbreviated publication name.
publication: "To appear in Proc. SIGGRAPH ASIA, December 2020."
publication_short: ""

abstract: "Neural networks are often quantized to use reduced-precision arithmetic, as it greatly improves their storage and computational costs. This approach is commonly used in applications like image classification and natural language processing, however, using a quantized network for the reconstruction of HDR images can lead to a significant loss in image quality. In this paper, we introduce QW-Net, a neural network for image reconstruction, where close to 95% of the computations can be implemented with 4-bit integers. This is achieved using a combination of two U-shaped networks that are specialized for different tasks, a feature extraction network based on the U-Net architecture, coupled to a filtering network that reconstructs the output image. The feature extraction network has more computational complexity but is more resilient to quantization errors. The filtering network, on the other hand, has significantly fewer computations but requires higher precision. Our network uses renderer-generated motion vectors to recurrently warp and accumulate previous frames, producing temporally stable results with significantly better quality than TAA, a widely used technique in current games."

# Summary. An optional shortened abstract.
summary: "We present QW-Net, a novel 4-bit quantized network that performs temporally amortized supersampling for high-dynamic-range rendering."

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

url_pdf: 
url_code:
url_dataset:
url_poster:
url_project: "https://creativecoding.soe.ucsc.edu/QW-Net/"
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
