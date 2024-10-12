---
title: "A smooth Crack-Band Model for anisotropic materials: Continuum theory and computations with the RKPM meshfree method"
authors:
- H. Nguyen
- J. Wang
- Y. Bazilevs
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2024-01-02T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*International Journal of Solids and Structures*, 288, 112618."
publication_short: ""

abstract: A smooth Crack Band Model (sCBM) is developed for anisotropic materials with both high and low magnitude of anisotropy. sCBM is primarily used as a regularization mechanism to enable capturing the correct size and shape of the fracture process zone (FPZ) as well as the smooth distribution of strain inside the zone. The versatility of the proposed sCBM formulation is demonstrated by its adaptability to any material law of choice. A Reproducing Kernel Particle Method (RKPM) is employed to discretize such formulation, the benefit of which is its ability to compute the Hessian of the displacement field (i.e., the sprain tensor), a key quantity in the sCBM theory, using only the nodal displacements as the problem unknowns. This makes the resulting formulation accurate and efficient, which is shown by the validations against size-effect and radial crushing experiments, illustrating the power of the proposed methodology for practical applications.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0045782523008344
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
