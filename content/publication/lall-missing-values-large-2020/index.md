---
title: "Missing Values in Large and Complex Data"
date: 2020-04-14
publishDate: 2020-05-02T20:36:30.580303Z
authors: ["Ranjit Lall", "Thomas Robinson"]
publication_types: ["10"]
abstract: "Principled methods for analyzing missing values, based chiefly on multiple imputation, have become increasingly popular among political scientists yet can struggle to handle the kinds of large and complex data that are also becoming common. We propose an accurate, fast, and scalable approach to multiple imputation, which we call MIDAS (Multiple Imputation with Denoising Autoencoders). MIDAS employs a class of unsupervised neural networks known as denoising autoencoders, which are designed to reduce dimensionality by corrupting and attempting to reconstruct a subset of data. We repurpose denoising autoencoders for multiple imputation by treating missing values as an additional portion of corrupted data and drawing imputations from a model trained to minimize the reconstruction error on the originally observed portion. Systematic tests involving simulated as well as real political data illustrate MIDAS's accuracy and efficiency across a range of settings. We provide open-source software for implementing MIDAS."
featured: false
publication: "*Under Review*"
doi: "10.33774/apsa-2020-3tk40-v3"
url_preprint: https://preprints.apsanet.org/engage/apsa/article-details/5e86309dc1eefd001adeb780
---

