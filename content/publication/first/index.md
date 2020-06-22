---
title: "Deep representation learning characterized by inter-class separation for image clustering"
authors:
- Dipanjan Das
- Ratul Ghosh
- Brojeshwar Bhowmick
date: "2019-01-01T00:00:00Z"
doi: "10.1109/WACV.2019.00072"

# Schedule page publish date (NOT publication's date).
publishDate: "2019-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *2019 IEEE Winter Conference on Applications of Computer Vision (WACV)*
#publication_short:

abstract: Despite significant advances in clustering methods in recent years, the outcome of clustering of a natural image dataset is still unsatisfactory due to two important drawbacks. Firstly, clustering of images needs a good feature representation of an image and secondly, we need a robust method which can discriminate these features for making them belonging to different clusters such that intra-class variance is less and inter-class variance is high. Often these two aspects are dealt with independently and thus the features are not sufficient enough to partition the data meaningfully. In this paper, we propose a method where we discover these features required for the separation of the images using deep autoencoder. Our method learns the image representation features automatically for the purpose of clustering and also select a coherent image and an incoherent image simultaneously for a given image so that the feature representation learning can learn better discriminative features for grouping the similar images in a cluster and at the same time separating the dissimilar images across clusters. Experiment results show that our method produces significantly better result than the state-of-the-art methods and we also show that our method is more generalized across different dataset without using any pre-trained model like other existing methods.

# Summary. An optional shortened abstract.
#summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

#tags:
#- Source Themes
# featured: false

links:
- name: Paper Link
  url: https://ieeexplore.ieee.org/abstract/document/8658417/
url_pdf: https://arxiv.org/pdf/1901.06474.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
#url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

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
#- internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
#slides: example
---
**Please cite using following bibtex:**
```
@INPROCEEDINGS{8658417,
  author={D. {Das} and R. {Ghosh} and B. {Bhowmick}},
  booktitle={2019 IEEE Winter Conference on Applications of Computer Vision (WACV)}, 
  title={Deep Representation Learning Characterized by Inter-Class Separation for Image Clustering}, 
  year={2019},
  volume={},
  number={},
  pages={628-637},}
  ```
