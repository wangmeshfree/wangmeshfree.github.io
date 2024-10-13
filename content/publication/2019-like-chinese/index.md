---
title: "A gradient smoothing Galerkin meshfree method for thin plate analysis with linear basis function"
authors:
- L. Deng
- D. Wang
- J. Wang
- J. Wu
# author_notes:
# - "Equal contribution"
# - "Equal contribution"
date: "2019-04-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Chinese Journal of Theoretical and Applied Mechanics*, 51(3), 690-702, in Chinese"
publication_short: ""

abstract: 薄板问题的控制方程为四阶微分方程，因而当采用伽辽金法进行分析时，形函数需要满足 C1 连续性要求，且至少使用二次基函数才能保证方法的收敛性. 无网格形函数虽然易于满足C1连续性要求，但由于不是多项式，其二阶导数的计算较为复杂耗时，同时也对刚度矩阵的数值积分提出了更高的要求. 本文提出了一种薄板分析的线性基梯度光滑伽辽金无网格法，该方法的基础是线性基无网格形函数的光滑梯度. 在梯度光滑构造的理论框架内，无网格形函数的二阶光滑梯度可以表示为形函数一阶梯度的线性组合，因而可以提高形函数二阶梯度的计算效率. 分析表明，线性基无网格形函数的光滑梯度不仅满足其固有的线性梯度一致性条件，还满足本属于二次基函数对应的额外高阶一致性条件，因此能够恰当地运用到薄板结构的伽辽金分析. 此外，插值误差分析也很好地验证了线性基无网格光滑梯度的收敛特性. 算例结果进一步表明，线性基梯度光滑伽辽金无网格法的收敛率与传统二次基伽辽金无网格法相当，但精度更高，同时刚度矩阵所需的高斯积分点数明显减少



tags:
- Source Themes
featured: false

# links:
# - name: ""
#   url: ""
url_pdf: https://lxxb.cstam.org.cn/en/article/doi/10.6052/0459-1879-19-004?utm_source=TrendMD&utm_medium=cpc&utm_campaign=Chinese_Journal_of_Theoretical_and_Applied_Mechanics_TrendMD_1
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
