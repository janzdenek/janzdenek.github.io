---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "MADAO: データ拡張最適化のためのメタ的アプローチ (English title: Meta Approach to Data Augmentation Optimization)"
authors: ["Ryuichiro Hataya", "Jan Zdenek", "Kazuki Yoshizoe", "Hideki Nakayama"]
date: 2020-08-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2020-09-24T20:27:03+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*The 23rd Meeting on Image Recognition and Understanding (MIRU 2020)*"
publication_short: "*MIRU 2020*"

abstract: "Data augmentation policies drastically improve the performance of image recognition tasks, especially when the policies are optimized for the target data and tasks. In this paper, we propose to optimize image recognition models and data augmentation policies simultaneously to improve the performance using gradient descent. Unlike prior methods, our approach avoids using proxy tasks or reducing search space, and can directly improve the validation performance. Our method achieves efficient and scalable training by approximating the gradient of policies by implicit gradient with Neumann series approximation. We demonstrate that our approach can improve the performance of various image classification tasks, including ImageNet classification and fine-grained recognition, without using dataset-specific hyperparameter tuning."

# Summary. An optional shortened abstract.
summary: ""

tags: ["non-peer-reviewed"]
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
