---
layout: post
title: "Efficient Image Splicing Localization via Contrastive Feature Extraction"
date: 2019-01-22 04:37:46
categories: arXiv_CV
tags: arXiv_CV CNN Gradient_Descent
author: Ronald Salloum, C.-C. Jay Kuo
mathjax: true
---

* content
{:toc}

##### Abstract
In this work, we propose a new data visualization and clustering technique for discovering discriminative structures in high-dimensional data. This technique, referred to as cPCA++, utilizes the fact that the interesting features of a "target" dataset may be obscured by high variance components during traditional PCA. By analyzing what is referred to as a "background" dataset (i.e., one that exhibits the high variance principal components but not the interesting structures), our technique is capable of efficiently highlighting the structure that is unique to the "target" dataset. Similar to another recently proposed algorithm called "contrastive PCA" (cPCA), the proposed cPCA++ method identifies important dataset specific patterns that are not detected by traditional PCA in a wide variety of settings. However, the proposed cPCA++ method is significantly more efficient than cPCA, because it does not require the parameter sweep in the latter approach. We applied the cPCA++ method to the problem of image splicing localization. In this application, we utilize authentic edges as the background dataset and the spliced edges as the target dataset. The proposed method is significantly more efficient than state-of-the-art methods, as the former does not require iterative updates of filter weights via stochastic gradient descent and backpropagation, nor the training of a classifier. Furthermore, the cPCA++ method is shown to provide performance scores comparable to the state-of-the-art Multi-task Fully Convolutional Network (MFCN).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.07172](http://arxiv.org/abs/1901.07172)

##### PDF
[http://arxiv.org/pdf/1901.07172](http://arxiv.org/pdf/1901.07172)

