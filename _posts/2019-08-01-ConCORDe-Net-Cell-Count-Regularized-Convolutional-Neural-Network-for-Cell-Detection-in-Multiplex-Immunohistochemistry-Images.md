---
layout: post
title: "ConCORDe-Net: Cell Count Regularized Convolutional Neural Network for Cell Detection in Multiplex Immunohistochemistry Images"
date: 2019-08-01 12:51:01
categories: arXiv_CV
tags: arXiv_CV Knowledge CNN Classification Deep_Learning Detection
author: Yeman Brhane Hagos, Priya Lakshmi Narayanan, Ayse U. Akarca, Teresa Marafioti, Yinyin Yuan
mathjax: true
---

* content
{:toc}

##### Abstract
In digital pathology, cell detection and classification are often prerequisites to quantify cell abundance and explore tissue spatial heterogeneity. However, these tasks are particularly challenging for multiplex immunohistochemistry (mIHC) images due to high levels of variability in staining, expression intensity, and inherent noise as a result of preprocessing artefacts. We proposed a deep learning method to detect and classify cells in mIHC whole-tumour slide images of breast cancer. Inspired by inception-v3, we developed Cell COunt RegularizeD Convolutional neural Network (ConCORDe-Net) which integrates conventional dice overlap and a new cell count loss function for optimizing cell detection, followed by a multi-stage convolutional neural network for cell classification. In total, 20447 cells, belonging to five cell classes were annotated by experts from 175 patches extracted from 6 whole-tumour mIHC images. These patches were randomly split into training, validation and testing sets. Using ConCORDe-Net, we obtained a cell detection F1 score of 0.873, which is the best score compared to three state of the art methods. In particular, ConCORDe-Net excels at detecting closely located and weakly stained cells compared to other methods. Incorporating cell count loss in the objective function regularizes the network to learn weak gradient boundaries and separate weakly stained cells from background artefacts. Moreover, cell classification accuracy of 96.5% was achieved. These results support that incorporating problem-specific knowledge such as cell count into deep learning-based cell detection architectures improve the robustness of the algorithm.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.00907](http://arxiv.org/abs/1908.00907)

##### PDF
[http://arxiv.org/pdf/1908.00907](http://arxiv.org/pdf/1908.00907)

