---
title: "Handwritten Text Generation with Character-specific Encoding for Style Imitation"

# Authors
# If you created a profile for a user (e.g. the default `me` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - me
  - Hideki Nakayama

date: '2023-08-01T00:00:00Z'

# Schedule page publish date (NOT publication's date).
publishDate: '2023-08-01T00:00:00Z'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: "*17th International Conference on Document Analysis and Recognition (ICDAR 2023)*"
publication_short: "*ICDAR 2023*"

abstract: "We propose a novel method for handwritten text generation that uses a style encoder based on a vision transformer network. The style encoder encodes handwriting style from reference images and allows the generator to imitate it. The encoder learns to disentangle style information from the content by learning to recognize who wrote the text. The self-attention mechanism in the encoder allows us to produce character-specific encodings by using characters in the target sequence as queries. Our method can generate handwritten text images in random styles by sampling random latent vectors. In comparison with existing methods, our method outperforms them for handwritten text generation in terms of the quality of generated images and their fidelity with respect to the distribution of real images. Our method also achieves significantly better performance at imitating handwriting styles defined by reference images. Furthermore, the model generalizes well to unseen data and can generate handwritten images of words and character sequences as well as imitate handwriting styles not included in the training data."

# Summary. An optional shortened abstract.
summary: ""

tags:
  - peer-reviewed

# Display this page in the Featured widget?
featured: false

# Standard identifiers for auto-linking
hugoblox:
  ids:
    doi: 10.1007/978-3-031-41679-8_18

# Custom links
links:
  - type: pdf
    url: "https://dl.acm.org/doi/10.1007/978-3-031-41679-8_18"

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
