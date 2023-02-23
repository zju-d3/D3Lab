---
title: 'UI Layers Group Detector: Grouping UI Layers via Text Fusion and Box Attention'
authors:
  - xsh
  - Zhou Tingting
  - cyn
  - 陈柳青
  - et al
date: '2023-01-01T00:00:00Z'
doi: ''

# Schedule page publish date (NOT publication's date).
publishDate: '2023-01-01T00:00:00Z'
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: In *Artificial Intelligence Second CAAI International Conference*
publication_short: In *CICAI 2022*


abstract: Graphic User Interface (GUI) is facing great demand with the popularization and prosperity of mobile apps. Automatic UI code generation from UI design draft dramatically simplifies the development process. However, the nesting layer structure in the design draft affects the quality and usability of the generated code. Few existing GUI automated techniques detect and group the nested layers to improve the accessibility of generated code. In this paper, we proposed our UI Layers Group Detector as a vision-based method that automatically detects images (i.e., basic shapes and visual elements) and text layers that present the same semantic meanings. We propose two plug-in components, text fusion and box attention, that utilize text information from design drafts as a priori information for group localization. We construct a large-scale UI dataset for training and testing, and present a data augmentation approach to boost the detection performance. The experiment shows that the proposed method achieves a decent accuracy regarding layers grouping.

# Summary. An optional shortened abstract.

tags:
  - Publication
featured: true

links:
  - name: Paper Link
    url: 'https://link.springer.com/chapter/10.1007/978-3-031-20500-2_25'
url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# image:
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
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
slides: ""
---

<!-- {{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

Supplementary notes can be added here, including [code and math](https://wowchemy.com/docs/content/writing-markdown-latex/). -->