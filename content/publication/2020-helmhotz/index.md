---
title: "A quasi-consistent integration method for efficient meshfree analysis of Helmholtz problems with plane wave basis functions"
authors:
- J. Wang
- J. Wu
- D. Wang
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2020-01-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Engineering Analysis with Boundary Elements*, 110, 42-55"
publication_short: ""

abstract: A quasi-consistent integration method is presented for the efficient meshfree analysis of Helmholtz problems. The plane wave basis functions are employed for the reproducing kernel meshfree approximation to accurately represent the acoustic field resulting from Helmholtz problems. In order to improve the computational efficiency of Galerkin meshfree analysis of Helmholtz problems, a reproducing kernel gradient smoothing approach is introduced into the meshfree formulation with plane wave basis functions. In the proposed method, the smoothed gradients of meshfree shape functions with plane wave basis functions are built upon a reproducing kernel gradient representation and the integration consistency of Galerkin meshfree formulation is implicitly ensured. Furthermore, a quasi-consistent integration scheme is proposed to compute the smoothed gradients, which aims to balance the efficiency and accuracy for meshfree analysis of Helmholtz problems. The proposed integration method leads to fully consistent integration when one wave direction is considered, and nearly consistent integration if two wave directions are taken into account, where the boundary sample points of integration cells are particularly preferred since they are simultaneously used by neighboring integration cells with efficiency gain. Numerical results demonstrate that the proposed methodology is much more efficient and accurate for Galerkin meshfree analysis of Helmholtz problems, in comparison with the standard meshfree formulations using high order Gauss quadrature rules.

# Summary. An optional shortened abstract.
summary: Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum.

tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0955799719306083
# url_code: 'https://github.com/HugoBlox/hugo-blox-builder'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  # caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
