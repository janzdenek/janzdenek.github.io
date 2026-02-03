---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Faster AutoAugment: Learning Augmentation Strategies using Backpropagation"
authors: ["Ryuichiro Hataya", "Jan Zdenek", "Kazuki Yoshizoe", "Hideki Nakayama"]
date: 2020-08-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-20T20:27:03+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*European Conference on Computer Vision (ECCV 2020)*"
publication_short: "*ECCV 2020*"

abstract: "Data augmentation methods are indispensable heuristics to boost the performance of deep neural networks, especially in image recognition tasks. Recently, several studies have shown that augmentation strategies found by search algorithms outperform hand-made strategies. Such methods employ black-box search algorithms over image transformations with continuous or discrete parameters and require a long time to obtain better strategies. In this paper, we propose a differentiable policy search pipeline for data augmentation, which is much faster than previous methods. We introduce approximate gradients for several transformation operations with discrete parameters as well as a differentiable mechanism for selecting operations. As the objective of training, we minimize the distance between the distributions of augmented and original data, which can be differentiated. We show that our method, Faster AutoAugment, achieves significantly faster searching than prior methods without a performance drop."

# Summary. An optional shortened abstract.
summary: ""

tags: ["peer-reviewed"]
categories: []
featured: false

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
