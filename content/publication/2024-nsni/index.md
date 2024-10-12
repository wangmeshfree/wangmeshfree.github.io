---
title: "Smoothed naturally stabilized RKPM for non-linear explicit dynamics with novel stress gradient update"
authors:
- J. Wang
- M. Hillman
- W. Dominic
- J. Magallanes
- Y. Bazilevs
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-06-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computational Mechanics*, 1-22"
publication_short: ""

abstract: A smoothed naturally stabilized conforming nodal integration (S-NSNI) for the reproducing kernel particle method (RKPM) is proposed for non-linear explicit dynamics. The Taylor series expansion of the nodal strains in the solid variational formulation is employed, which introduces stabilization by enriching the energy of the originally underintegrated system. As a result, the higher-order gradients of meshfree shape functions are required, and are approximated by using the gradient smoothing technology. In conjunction with implicit gradients, this results in a formulation devoid of computationally intensive differentiation of meshfree shape functions. In addition, when conforming smoothing domains are employed, the formulation is variationally consistent and converges optimally while passing the patch test. The smoothed framework further alleviates a numerical locking in the original NSNI by avoiding direct differentiation that leads to inaccuracies in stabilization terms. To enhance the nontrivial computation of the required stress gradients or estimates there of, a novel stress re-interpolation methodology is introduced, which is favorable for the implementation of arbitrary constitutive laws such as those in commercial codes, which are often plentiful. The framework is developed for both Lagrangian and semi-Lagrangian RKPM and is applicable to both moderate and extreme deformations. The effectiveness of the proposed methodology is demonstrated by the implementation into the KC-FEMFRE and MEGA codes and applied to several benchmark problems that include elastic, nearly incompressible, and plastic materials, as well as geomaterial modeling using continuum damage mechanics coupled with plasticity.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://link.springer.com/article/10.1007/s00466-024-02494-0
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
