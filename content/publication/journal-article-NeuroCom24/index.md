---
title: 'Element-conditioned GAN for graphic layout generation'
authors:
  - 陈柳青
  - jqz
  - Yunzhan Zhou
  - Zhaoxing Li
  - Lei Shi
  - Lingyun Sun
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: '2024-04-23T00:00:00Z'
doi: 'https://doi.org/10.1016/j.neucom.2024.127730'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-04-23T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Neurocomputing*
# publication_short: In *CICAI 2022*


abstract: Layout guides the position and scale of design elements for desirable aesthetics and effective demonstration. Recently, Generative Adversarial Networks (GANs) have proved their capability in generating effective layouts. However, current GANs ignore the situation where the amounts and types of the input design elements are given and determined. In this paper, we propose EcGAN, an element-conditioned GAN for graphic layout generation conditioned on specified design elements (design elements’ amount and types). We represent each element by a bounding box and propose three components:element mask, element condition loss and two-step discriminators, to solve the bounding box modelling problem for element-conditioned layout generation. Experiments reveal that EcGAN outperforms existing methods quantitatively and qualitatively. We also perform detailed ablation studies to highlight the effect of each component and a user study to further validate our model. Finally, we demonstrate two of EcGAN’s applications for practical design scenarios.


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