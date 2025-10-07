---
title: 'AskNatureNet: A divergent thinking tool based on bio-inspired design knowledge'
authors:
  - 陈柳青
  - czb
  - jzj
  - Jianxi Luo
  - Lingyun Sun
  - Peter RN Childs
  - Haoyu Zuo
# author_notes:
#   - 'Equal contribution'
#   - 'Equal contribution'
date: '2024-05-28T00:00:00Z'
doi: 'https://doi.org/10.1016/j.aei.2024.102593'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-05-28T00:00:00Z'

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: In *Advanced Engineering Informatics*
# publication_short: In *CICAI 2022*


abstract: Divergent thinking is a process in design by exploring multiple possible solutions, is crucial in the early stages of design to break fixation and expand the design ideation. Design-by-Analogy promotes divergent thinking, by studying solutions have solved similar problems and using this knowledge to make inferences and solve problems in new and unfamiliar situations. Bio-inspired design (BID) is a form of design by analogy and its knowledge provides diverse sources for analogy, making BID knowledge as a potential source for divergent thinking. Existing BID database has focused on collecting BID cases and facilitating the retrieval of biological knowledge. Despite its success, applying BID knowledge into divergent thinking still encounters challenge, as the association between source domain and target domain are always limited within a single case. In this work, a novel approach is proposed to support divergent thinking from three subsequent phases:encoding, retrieval and mapping. Specifically, biological knowledge is encoded in a triple form by employing a large language model (LLM) to extract key information from a well-known BID knowledge base. The created triples are implemented in a semantic network to facilitate bidirectional retrieval modes:problem-driven and solution-driven, as well as mapping for divergent thinking. The mapping algorithm calculates the semantic similarity between nodes in the semantic network based on their attributes in three progressive steps by following the paradigm of divergent thinking. The proposed approach is implemented as tool called AskNatureNet,1 which supports divergent thinking by retrieving and mapping knowledge in a visualized interactive semantic network. An ideation case study on evaluating the effectiveness of AskNatureNet shows that our tool is capable of supporting divergent thinking efficiently.


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