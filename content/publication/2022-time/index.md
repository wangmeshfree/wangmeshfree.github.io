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
publication: "*Computer Methods in Applied Mechanics and Engineering*, 393, 114738"
publication_short: ""

abstract: Non-symmetric matrices may arise in the discretization of self-adjoint problems when a Petrov–Galerkin, collocation, or finite-volume method is employed. While these methods have been widely applied, in this paper it is shown that the use of these non-symmetric matrices is incompatable with the conservation of energy in elastodynamics. First, the consistency between the continuous forms of the momentum equation and the energy equation is examined. It is shown that the conservation of linear momentum is equivalent to conservation of energy provided the solution is sufficiently smooth. The semi-discrete counterparts are then analyzed, where it is demonstrated that they are also equivalent, but only conditionally: the mass and stiffness matrices must be symmetric. As a result, employing a non-symmetric method in elastodynamics may artificially generate or dissipate energy. The fully discrete forms with Newmark time integration are then examined where it is shown that unconditionally unstable algorithms may arise. An energy-conserving time integration algorithm is then proposed which provides stability in the solutions of non-symmetric systems. The collocation and finite-volume methods are employed in numerical examples to demonstrate stability issues and the effectiveness of the proposed time integration methodology.


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
