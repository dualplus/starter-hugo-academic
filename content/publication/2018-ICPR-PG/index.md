---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Patch-gated CNN for Occlusion-aware Facial Expression Recognition"
authors:
- Yong Li
- admin
- Shiguang Shan
- Xilin Chen

date: 2018-08-16T21:24:05+08:00
doi: ""


# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "International Conference on Pattern Recognition (ICPR), 2018. [Oral]"
publication_short: ""

abstract: "Facial expression recognition in the wild is challenging due to various un-constrained conditions. Although existing facial expression classifiers have been almost perfect on analyzing constrained frontal faces, they fail to perform well on partially occluded faces that are common in the wild. In this paper, we propose an end-to-end trainable Patch-Gated Convolution Neutral Network (PG-CNN) that can automatically percept the occluded region of the face and focus on the most discriminative un-occluded regions. To determine the possible regions of interest on the face, PG-CNN decomposes an intermediate feature map into several patches according to the positions of related facial landmarks. Then, via a proposed Patch-Gated Unit, PG-CNN reweighs each patch by the unobstructed-ness or importance that is computed from the patch itself. The proposed PG-CNN is evaluated on two largest in-the-wild facial expression datasets (RAF-DB and AffectNet) and their modifications with synthesized facial occlusions. Experimental results show that PG-CNN improves the recognition accuracy on both the original faces and faces with synthesized occlusions. Visualization results demonstrate that, compared with the CNN without Patch-Gated Unit, PG-CNN is capable of shifting the attention from the occluded patch to other related but unobstructed ones. Experiments also show that PG-CNN outperforms other state-of-the-art methods on several widely used in-the-lab facial expression datasets under the cross-dataset evaluation protocol."

# Summary. An optional shortened abstract.
summary: "in International Conference on Pattern Recognition (ICPR), 2018. [Oral]"

tags: ["FER"]
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_pdf: "http://www.jdl.link/doc/2011/201911019432863571_2018092516364248.pdf"
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
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['Emotion']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
