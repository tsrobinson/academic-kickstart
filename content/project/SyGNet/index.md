---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Synthetic data using Generative Adversarial Networks (SyGNet)"
summary: ""
authors: []
tags: []
categories: []
date: 2021-09-07T17:16:32+01:00

# Optional external URL for project (replaces project detail page).
external_link: ""

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Custom links (optional).
#   Uncomment and edit lines below to show custom links.
# links:
# - name: Follow
#   url: https://twitter.com
#   icon_pack: fab
#   icon: twitter

url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


*SyGNet (**Sy**nthetic data using **G**enerative Adversarial **Net**works) is an 18-month project funded by a British Academy/Leverhulme Trust Small Project grant (£33k FEC, £10k cost to funder).*

Social science data is both incredibly diverse and complex. From chaotic and noisy data generating processes, researchers aim to make concrete inferential claims about social phenomena. At the forefront of social science research, novel techniques and statistical methods are being developed to enable researchers to make robust inferential claims amid this complexity. Effective use of these tools and methods rests on demonstrations of their performance, which in turn relies on using the right kind of data to test them. Yet simulations are hard to conduct well precisely because real social science data is so complex. Overly simplified tests using parametric data may not comport well with actual social science applications. Conversely, benchmarking on well-known studies or datasets leaves researchers unable to estimate bias since the population parameters are unknown.

In this project I propose to help solve this tension by using synthetic data: a strategy in which the underlying relationships between variables in real-world data are learned, and from which an arbitrary number of entirely new but realistic observations can be generated (i.e. “synthesised”). Creating synthetic data is a recent but increasingly popular method of analysis. Synthetic data is already used to run public analyses without compromising personally-identifying information of real-world subjects (eg Wang and Docherty 2006, Zięba et al 2016, Assefa 2020), to train predictive models with few, naturally occurring observations (eg Wang et al 2019, Zhang et al 2019) or, in my own research, to increase the predictive power of multiple imputation models (Lall and Robinson 2021).

To effectively model the complexity of real-world data, this project will construct synthetic datasets using generative adversarial networks (GANs) -- a form of deep learning. GANs are a class-leading solution for detecting and modelling complex, non-parametric relationships within data. Specifically, in a GAN, two separate neural networks "compete" against each other in an effort to produce ever-more realistic looking data. One network constructs new observations, and the second network aims to detect which observations are real. By training these two networks in tandem, the GAN becomes highly proficient at reproducing data that looks like real data. GANs are notably good, for instance, at generating fake photo-realistic portraits (eg Karras et al 2017).

With a team of two research assistants (one hire pending) we will develop the underlying neural network architecture, collate relevant social science data, and demonstrate the practical utility of this method to applied methodologists and social scientists.