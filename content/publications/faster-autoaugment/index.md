---
title: "Faster AutoAugment: Learning Augmentation Strategies using Backpropagation"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ryuichiro Hataya
  - me
  - Kazuki Yoshizoe
  - Hideki Nakayama

date: '2020-08-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-09-20T20:27:03+09:00'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*European Conference on Computer Vision (ECCV 2020)*"
publication_short: "*ECCV 2020*"

abstract: "Data augmentation methods are indispensable heuristics to boost the performance of deep neural networks, especially in image recognition tasks. Recently, several studies have shown that augmentation strategies found by search algorithms outperform hand-made strategies. Such methods employ black-box search algorithms over image transformations with continuous or discrete parameters and require a long time to obtain better strategies. In this paper, we propose a differentiable policy search pipeline for data augmentation, which is much faster than previous methods. We introduce approximate gradients for several transformation operations with discrete parameters as well as a differentiable mechanism for selecting operations. As the objective of training, we minimize the distance between the distributions of augmented and original data, which can be differentiated. We show that our method, Faster AutoAugment, achieves significantly faster searching than prior methods without a performance drop."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - peer-reviewed

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-030-58595-2_1

# Custom links
links:
  - type: pdf
    url: "https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123700001.pdf"

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
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
