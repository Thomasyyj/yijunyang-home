---
title: "UniArk: Improving Generalisation and Consistency for Factual Knowledge Extraction through Debiasing"
authors:
- admin
- Jie He
- Pinzhen Chen
- Victor Gutierrez Basulto
- Jeff Z. Pan
date: "2023-12-15T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
# publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# publication_types: ["article"]

# Publication name and optional abbreviated publication name.
publication: "*NAACL 2024 under peer review*"
# publication_short: ""

abstract: In recent years, several works have investigated the potential  of language models as knowledge bases as well as the existence of severe biases when extracting factual knowledge. In this work, we point out the inherent misalignment between pre-training and downstream tuning objectives in language models for probing knowledge under a probabilistic view and hypothesize that simultaneously debiasing these objectives can be the key to generalisation over unseen prompts.  We propose an adapter-based framework **UniArk** for generalised and consistent  factual knowledge extraction through simple and parameter-free methods. Extensive experiments show that UniArk can significantly improve the model's out-of-domain generalisation as well as being consistent under various prompts. Additionally, we construct a large-scale and diverse dataset **ParaTrex** for measuring the inconsistency and out-of-domain generation of models. Further, ParaTrex offers a reference method for constructing paraphrased datasets using large language models

# Summary. An optional shortened abstract.
# summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

links:
# - name: Custom Link
#   url: http://example.org
url_pdf: https://openreview.net/pdf?id=YMn51UxIjeq
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
#   caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/s9CC2SKySJM)'
#   focal_point: ""
#   preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
# projects:
# - internal-project

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
# slides: example
---

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://wowchemy.com/docs/content/writing-markdown-latex/).
