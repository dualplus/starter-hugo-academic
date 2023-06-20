---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Source-Free Adaptive Gaze Estimation by Uncertainty Reduction"
authors:
- Xin Cai
- admin
- shanshiguang
- chenxilin

date: 2023-06-19T18:5:51+08:00
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: 2023-06-19T18:54:51+08:00

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition(CVPR), 2023"
#publication_short: "CVPR2023"

abstract: "Gaze estimation across domains has been explored recently because the training data are usually collected under controlled conditions while the trained gaze estimators are used in real and diverse environments. However, due to privacy and efficiency concerns, simultaneous access to annotated source data and to-be-predicted target data can be challenging. In light of this, we present an unsupervised source-free domain adaptation approach for gaze estimation, which adapts a source-trained gaze estimator to unlabeled target domains without source data. We propose the Uncertainty Reduction Gaze Adaptation (UnReGA) framework, which achieves adaptation by reducing both sample and model uncertainty. Sample uncertainty is mitigated by enhancing image quality and making them gaze-estimation-friendly, whereas model uncertainty is reduced by minimizing prediction variance on the same inputs. Extensive experiments are conducted on six cross-domain tasks, demonstrating the effectiveness of UnReGA and its components. Results show that UnReGA outperforms other state-of-the-art cross-domain gaze estimation methods under both protocols, with and without source data."

# Summary. An optional shortened abstract.
summary: "in Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition(CVPR), 2023."

tags: ['selected','gaze-estimation']
categories: []
featured: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
links:
 - name: Suppl.
   url: https://openaccess.thecvf.com/content/CVPR2023/supplemental/Cai_Source-Free_Adaptive_Gaze_CVPR_2023_supplemental.pdf
#   icon_pack: fab
#   icon: twitter

url_pdf: https://openaccess.thecvf.com/content/CVPR2023/papers/Cai_Source-Free_Adaptive_Gaze_Estimation_by_Uncertainty_Reduction_CVPR_2023_paper.pdf
url_code: https://github.com/caixin1998/UnReGA
url_dataset:
url_poster: poster.pdf
url_project:
url_slides:
url_source:
url_video: video.mp4

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: Smart
  preview_only: true

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['3D_gaze']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""
---
