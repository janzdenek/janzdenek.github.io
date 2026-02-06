---
title: "Erasing Scene Text With Weak Supervision"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Hideki Nakayama

date: '2019-11-25T15:00:24+09:00'

# Schedule page publish date (NOT publication's date).
publishDate: '2019-11-25T15:00:24+09:00'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*Proceedings of the 2020 IEEE Winter Conference on Applications of Computer Vision (WACV 2020)*"
publication_short: "*WACV 2020*"

abstract: "Scene text erasing is a task of removing text from natural scene images, which has been gaining attention in recent years. The main motivation is to conceal private information such as license plate numbers and house nameplates that can appear in images. In this work, we propose a novel method for scene text erasing that approaches the problem as a general inpainting task. Unlike previous methods, which require pairs of original images containing text and images with the text removed, our method does not need corresponding image pairs for training. We use a separately trained scene text detector and an inpainting network. The scene text detector predicts segmentation maps of text instances, which are then used as masks for the inpainting network. The network for inpainting, trained on the Places2 dataset of indoors and outdoors scenes, fills in masked out regions in an input image and generates a final image with erased text. The results show that our method is able to remove text from images and naturally fill in the background."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - peer-reviewed

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1109/WACV45572.2020.9093544

# Custom links
links:
  - type: pdf
    url: "https://openaccess.thecvf.com/content_WACV_2020/papers/Zdenek_Erasing_Scene_Text_with_Weak_Supervision_WACV_2020_paper.pdf"

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
