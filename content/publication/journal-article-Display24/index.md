---
title: 'UI semantic component group detection: Grouping UI elements with similar semantics in mobile graphical user interface'
authors:
  - xsh
  - cyn
  - syx
  - 陈柳青
  - Lingyun Sun
  - et al
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: '2024-03-15T00:00:00Z'
doi: 'https://doi.org/10.1016/j.displa.2024.102679'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-03-15T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Displays*
# publication_short: In *CICAI 2022*


abstract: Texts, widgets, and images on a UI page do not work separately. Instead, they are partitioned into groups to achieve certain interaction functions or visual information. Existing studies on UI elements grouping mainly focus on a specific single UI-related software engineering task, and their groups vary in appearance and function. In this case, we propose our semantic component groups that pack adjacent text and non-text elements with similar semantics. In contrast to those task-oriented grouping methods, our semantic component group can be adopted for multiple UI-related software tasks, such as retrieving UI perceptual groups, improving code structure for automatic UI-to-code generation, and generating accessibility data for screen readers. To recognize semantic component groups on a UI page, we propose a robust, deep learning-based vision detector, UISCGD, which extends the SOTA deformable-DETR by incorporating UI element color representation and a learned prior on group distribution. The model is trained on our UI screenshots dataset of 1988 mobile GUIs from more than 200 apps in both iOS and Android platforms. The evaluation shows that our UISCGD achieves 6.1% better than the best baseline algorithm and 5.4 % better than deformable-DETR in which it is based.


# summary: An optional shortened abstract.

tags:
  - Publication
  - SCI
featured: false


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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
#   focal_point: ''
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: 

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