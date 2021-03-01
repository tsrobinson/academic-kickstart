---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'The MIDAS Touch: Accurate and Scalable Missing-Data Imputation with Deep Learning'
subtitle: ''
summary: ''
authors:
- Ranjit Lall
- Thomas Robinson
tags: ["a"]
categories: []
date: '2020-10-01'
lastmod: 2020-12-15T23:26:38Z
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ''
  focal_point: ''
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
publishDate: '2020-12-15T23:26:38.197311Z'
publication_types:

- '2'
abstract: Principled methods for analyzing missing values, based chiefly on multiple
  imputation, have become increasingly popular yet can struggle to handle the kinds
  of large and complex data that are also becoming common. We propose an accurate,
  fast, and scalable approach to multiple imputation, which we call MIDAS (Multiple
  Imputation with Denoising Autoencoders). MIDAS employs a class of unsupervised neural
  networks known as denoising autoencoders, which are designed to reduce dimensionality
  by corrupting and attempting to reconstruct a subset of data. We repurpose denoising
  autoencoders for multiple imputation by treating missing values as an additional
  portion of corrupted data and drawing imputations from a model trained to minimize
  the reconstruction error on the originally observed portion. Systematic tests on
  simulated as well as real social science data, together with an applied example
  involving a large-scale electoral survey, illustrate MIDAS's accuracy and efficiency
  across a range of settings. We provide open-source software for implementing MIDAS.
publication: '*Political Analysis*'
url_pdf: http://eprints.lse.ac.uk/108170/1/Lall_Robinson_PA_Forthcoming.pdf
doi: 10.1017/pan.2020.49
---
