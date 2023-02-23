---
title: 'UI Layers Merger: Merging UI layers via Visual Learning and Boundary Prior'
authors:
  - cyn
  - Zhen Yankun
  - Shi chuning
  - ljz
  - 陈柳青
  - et al
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: '2022-06-18T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2022-06-18T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Frontiers of Information Technology & Electronic Engineering*
# publication_short: In *CICAI 2022*


abstract: With the fast-growing GUI development workload in the Internet industry, some work on intelligent methods attempted to generate maintainable front-end code from UI screenshots. It can be more suitable for utilizing UI design drafts that contain UI metadata. However, fragmented layers inevitably appear in the UI design drafts which greatly reduces the quality of code generation. None of the existing GUI automated techniques detects and merges the fragmented layers to improve the accessibility of generated code. In this paper, we propose UI Layers Merger (UILM), a vision-based method, which can automatically detect and merge fragmented layers into UI components. Our UILM contains Merging Area Detector (MAD) and a layers merging algorithm. MAD incorporates the boundary prior knowledge to accurately detect the boundaries of UI components. Then, the layers merging algorithm can search out the associated layers within the components' boundaries and merge them into a whole part. We present a dynamic data augmentation approach to boost the performance of MAD. We also construct a large-scale UI dataset for training the MAD and testing the performance of UILM. The experiment shows that the proposed method outperforms the best baseline regarding merging area detection and achieves a decent accuracy regarding layers merging.


# summary: An optional shortened abstract.

tags:
  - Publication
featured: false

links:
- name: Paper Link
  url: 'https://arxiv.org/abs/2206.13389'
url_pdf: ''
url_code: 'https://github.com/zju-d3/uilm'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 
  - project_3
# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides:
---
<!-- 
{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/). -->