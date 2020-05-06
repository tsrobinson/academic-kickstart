---
title: "Midas: Efficient Multiple Imputation for Large and Complex Data in Python"
date: 2020-04-15
publishDate: 2020-05-02T20:36:30.580085Z
authors: ["Ranjit Lall", "Alex Stenlake", "Thomas S Robinson"]
publication_types: ["9"]
abstract: "This paper introduces midas, a Python class for multiply imputing missing values based on neural network methods that is particularly well suited to large and complex data. midas implements a new approach to multiple imputation that involves introducing an additional portion of missingness into the dataset, attempting to reconstruct this portion with a type of unsupervised neural network known as a denoising autoencoder, and using the resulting model to draw imputations of originally missing values. These steps are implemented with a fast, scalable, and flexible algorithm that expands both the quantity and the range of data that can be analyzed with multiple imputation. To help users optimize the algorithm for their specific application, midas offers a variety of user-friendly tools for calibrating and validating the imputation model. We provide a comprehensive guide to these functionalities and demonstrate their usage on a sizable real dataset."
featured: false
publication: "Working Paper"
---
