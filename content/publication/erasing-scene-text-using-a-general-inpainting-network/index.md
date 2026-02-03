---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Erasing Scene Text Using a General Inpainting Network"
authors: ["Jan Zdenek", "Hideki Nakayama"]
date: 2019-07-01
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2019-06-08T19:23:48+09:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent; 9 = peer-reviewed; 10 = without peer review
publication_types: ["paper-conference"]

# Publication name and optional abbreviated publication name.
publication: "*The 22nd Meeting on Image Recognition and Understanding (MIRU 2019)*."
publication_short: "*MIRU 2019*"

abstract: "Scene text erasing is a task of removing text from natural scene images, which has been gaining attention in recent years. The main motivation is to conceal private information such as license plate numbers, and house name plates that can appear in images. In this work, we propose a novel method for scene text erasing that approaches the problem as a general inpainting task. Unlike previous methods, which require pairs of original images containing text and images with the text removed, our method does not need corresponding image pairs for training. We use a separately trained scene text detector and an inpainting network. The scene text detector predicts segmentation maps of text instances, which are then used as masks for the inpainting network. The network for inpainting, trained on the Places2 dataset of indoors and outdoors scenes, fills in masked out regions in an input image and generates a final image with erased text. The results show that our method is able to remove text from images and naturally fill in the background."

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
