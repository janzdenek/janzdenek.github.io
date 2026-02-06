---
title: "OTR: Synthesizing Overlay Text Dataset for Text Removal"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Wataru Shimoda
  - Kota Yamaguchi

date: '2025-10-27T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2025-10-27T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*33rd ACM International Conference on Multimedia (ACMMM 2025) - Datasets Track*"
publication_short: "*ACMMM 2025*"

abstract: "Text removal is a crucial task in computer vision with applications such as privacy preservation, image editing, and media reuse. While existing research has primarily focused on scene text removal in natural images, limitations in current datasets hinder out-of-domain generalization or accurate evaluation. In particular, widely used benchmarks such as SCUT-EnsText suffer from ground truth artifacts due to manual editing, overly simplistic text backgrounds, and evaluation metrics that do not capture the quality of generated results. To address these issues, we introduce an approach to synthesizing a text removal benchmark applicable to domains other than scene texts. Our dataset features text rendered on complex backgrounds using object-aware placement and vision-language model-generated content, ensuring clean ground truth and challenging text removal scenarios. We demonstrate through extensive evaluations that training on our dataset significantly improves performance and generalization on existing benchmarks."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - peer-reviewed

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3746027.3758297

# Custom links
links:
  - type: pdf
    url: "https://arxiv.org/abs/2510.02787v1"
  - type: code
    url: ""
  - type: dataset
    url: "https://huggingface.co/datasets/cyberagent/OTR"

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
