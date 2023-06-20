---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Confidence Preserving Machine for Facial Action Unit Detection"
authors:
- admin
- Wen-Sheng Chu
- Fernando de la Torre
- Jeffery F. Cohn
- Zhang Xiong

date: 2015-12-08T21:26:43+08:00
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the IEEE International Conference on Computer Vision (ICCV), 2015"
publication_short: ""

abstract: "Varied sources of error contribute to the challenge of facial action unit detection. Previous approaches address specific and known sources. However, many sources are unknown. To address the ubiquity of error, we propose a Confident Preserving Machine (CPM) that follows an easy-to-hard classification strategy. During training, CPM learns two confident classifiers. A confident positive classifier separates easily identified positive samples from all else; a confident negative classifier does same for negative samples. During testing, CPM then learns a person-specific classifier using ``virtual labels'' provided by confident classifiers. This step is achieved using a quasi-semi-supervised (QSS) approach. Hard samples are typically close to the decision boundary, and the QSS approach disambiguates them using spatio-temporal constraints. To evaluate CPM, we compared it with a baseline single-margin classifier and state-of-the-art semi-supervised learning, transfer learning, and boosting methods in three datasets of spontaneous facial behavior. With few exceptions, CPM outperformed baseline and state-of-the art methods."

# Summary. An optional shortened abstract.
summary: "in Proceedings of the IEEE International Conference on Computer Vision (ICCV), 2015."

tags: ['AU']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
#- name: code
#  url: "../publication/tip2016-cpm/cpm_demo.zip"
#   icon_pack: fab
#   icon: twitter

url_pdf: "https://openaccess.thecvf.com/content_iccv_2015/papers/Zeng_Confidence_Preserving_Machine_ICCV_2015_paper.pdf"
url_code:
url_dataset:
url_poster: "poster.pdf"
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
projects: ["AU"]

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
