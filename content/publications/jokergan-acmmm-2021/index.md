---
title: "JokerGAN: Memory-Efficient Model for Handwritten Text Generation with Text Line Awareness"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Hideki Nakayama

date: '2021-10-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2021-10-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*29th ACM International Conference on Multimedia (ACMMM 2021)*"
publication_short: "*ACMMM 2021*"

abstract: "Collecting labeled data for training of models for image recognition problems, including handwritten text recognition (HTR), is a tedious and expensive task. Recent work on handwritten text generation shows that generative models can be used as a data augmentation method to improve the performance of HTR systems. We propose a new method for handwritten text generation that uses generative adversarial networks with multi-class conditional batch normalization, which enables us to use character sequences with variable lengths as conditional input. Compared to existing methods, our model has significantly lower memory requirements which are almost constant regardless of the size of the character set. This allows us to train a generative model for languages with a large number of characters, such as Japanese. An additional condition makes the generator aware of vertical properties of the characters in the generated sequence, which helps us generate text with well-aligned characters in the text line. Our experiments on handwritten text datasets show that the proposed model can be used to boost the performance of HTR, particularly when we only have access to partially annotated data and train the generative model in a semi-supervised fashion. Our results also show that our model outperforms the current state-of-the-art for handwritten text generation. In addition, a human evaluation study indicates that the proposed method generates handwritten text images that look more realistic and natural."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - peer-reviewed

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1145/3474085.3475713

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/10.1145/3474085.3475713"

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
