---
# Documentation: https://wowchemy.com/docs/managing-content/

title: 'midas: Efficient Multiple Imputation for Large and Complex Data in Python'
subtitle: ''
summary: ''
authors:
- Ranjit Lall
- Alex Stenlake
- Thomas Robinson
tags: []
categories: []
date: '2020-04-01'
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
publishDate: '2020-12-15T23:26:38.368461Z'
publication_types:
- '3'
abstract: This paper introduces software packages for efficiently imputing missing
  data using deep learning methods in Python (MIDASpy) and R (rMIDAS). The software
  implements a recently developed approach to multiple imputation known as MIDAS,
  which involves introducing an additional portion of missingness into the dataset,
  attempting to reconstruct this portion with a type of unsupervised neural network
  known as a denoising autoencoder, and using the resulting model to draw imputations
  of originally missing values. These steps are executed by a fast, scalable, and
  flexible algorithm that expands both the quantity and the range of data that can
  be analyzed with multiple imputation. To help users optimize the algorithm for their
  specific application, MIDASpy and rMIDAS offer a host of user-friendly tools for
  calibrating and validating the imputation model. We provide a comprehensive guide
  to these functionalities and demonstrate their usage on a large real dataset.
publication: '*Working Paper*'
---
