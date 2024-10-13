---
title: "Temporal stability of collocation, Petrov–Galerkin, and other non-symmetric methods in elastodynamics and an energy conserving time integration"
authors:
- J. Wang
- M. Hillman
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2022-07-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Computer Methods in Applied Mechanics and Engineering*, 420, 116711"
publication_short: ""

abstract: Because of the best approximation property, traditional Bubnov–Galerkin numerical methods have proven immensely successful in modeling self-adjoint problems, such as heat conduction, elasticity, and so on. However, a numerical instability arises in these (and central finite difference) methods for problems with strong convection. In this class of problems, the convective transport term can lead to large spurious oscillations but can be handled by the class of Petrov–Galerkin methods. In particular, the upwind-type schemes and their variational and subgrid descendants have been substantially developed over the years for an effective weak-form Galerkin solution that precludes these instabilities. Nevertheless, the scale of development of upwind methods for strong-form collocation is substantially smaller, where numerical oscillations are also observed when they are straightforwardly applied to convection-dominated problems without special treatment. To this end, this paper presents a new upwind collocation method. First, the connection between the upwind finite difference scheme and the gradient smoothing technique in meshfree methods is established. It is then shown that selecting the collocation points as meshfree nodal points is not optimal; selecting the collocation points according to the flow direction and Péclet number is then studied. The upwind effect is achieved without introducing artificial parameters and is trivial to generalize for multi-dimensional cases. Cross-wind diffusion is also not observed in the solution. An error analysis is presented, and the effectiveness of the proposed methodology is well demonstrated by the steady and unsteady numerical examples.


tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://www.sciencedirect.com/science/article/pii/S0045782522000950
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
