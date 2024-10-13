---
title: "A review of numerical integration approaches for Galerkin meshfree methods"
authors:
- J. Wu
- J. Deng
- J. Wang
- D. Wang
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2016-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Chinese Journal of Solid Mechanics*, 37.3 (2016): 208-233, in Chinese"
publication_short: ""

abstract: 无网格法直接通过节点信息构造形函数,不依赖于节点之间的有序单元连接,能够建立任意高阶连续的整体协调形函数.与传统的有限元法相比,无网格法对大变形问题,移动边界问题和高阶问题的求解有比较明显的优势.伽辽金型无网格法是目前应用最为广泛的一类无网格法.虽然无网格形函数本身不依赖于单元,但伽辽金型无网格法需要采取合适的方法进行弱形式的数值积分.由于无网格形函数一般不是多项式,具有非插值性且影响域与背景积分网格通常不重合,伽辽金型无网格法通常需要采用高阶的高斯积分进行数值积分,导致了计算效率低下,难于求解大型实际问题.因此,如何通过建立高效积分方法提高无网格法的计算效率成为无网格法研究领域的一个核心问题.论文总结了伽辽金型无网格法中若干常用的数值积分方法,并对伽辽金型无网格法的数值积分方法领域存在的一些问题进行了探讨.




tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://pubs.cstam.org.cn/article/id/cjsm_gtlxxb201603002
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
