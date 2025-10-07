---
title: 'Neurocognition-inspired design with machine learning'
authors:
  - Pan Wang
  - Shuo Wang
  - Danlin Peng
  - 陈柳青
  - et al
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: '2020-12-17T00:00:00Z'
doi: 'https://doi.org/10.1017/dsj.2020.23'

# Schedule page publish date (NOT publication's date).
publishDate: '2020-12-17T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Design Science*
# publication_short: In *CICAI 2022*


abstract: Generating designs via machine learning has been an on-going challenge in computer-aided design. Recently, deep learning methods have been applied to randomly generate images in fashion, furniture and product design. However, such deep generative methods usually require a large number of training images and human aspects are not taken into account in the design process. In this work, we seek a way to involve human cognitive factors through brain activity indicated by electroencephalographic measurements (EEG) in the generative process. We propose a neuroscience-inspired design with a machine learning method where EEG is used to capture preferred design features. Such signals are used as a condition in generative adversarial networks (GAN). First, we employ a recurrent neural network Long Short-Term Memory as an encoder to extract EEG features from raw EEG signals; this data are recorded from subjects viewing several categories of images from ImageNet. Second, we train a GAN model conditioned on the encoded EEG features to generate design images. Third, we use the model to generate design images from a subject’s EEG measured brain activity. To verify our proposed generative design method, we present a case study, in which the subjects imagine the products they prefer, and the corresponding EEG signals are recorded and reconstructed by our model for evaluation. The results indicate that a generated product image with preference EEG signals gains more preference than those generated without EEG signals. Overall, we propose a neuroscience-inspired artificial intelligence design method for generating a design taking into account human preference. The method could help improve communication between designers and clients where clients might not be able to express design requests clearly.


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