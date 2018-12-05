---
layout: post
title: "Disease Detection in Weakly Annotated Volumetric Medical Images using a Convolutional LSTM Network"
date: 2018-12-03 21:32:28
categories: arXiv_CV
tags: arXiv_CV CNN RNN Detection
author: Nathaniel Braman, David Beymer, Ehsan Dehghan
mathjax: true
---

* content
{:toc}

##### Abstract
We explore a solution for learning disease signatures from weakly, yet easily obtainable, annotated volumetric medical imaging data by analyzing 3D volumes as a sequence of 2D images. We demonstrate the performance of our solution in the detection of emphysema in lung cancer screening low-dose CT images. Our approach utilizes convolutional long short-term memory (LSTM) to "scan" sequentially through an imaging volume for the presence of disease in a portion of scanned region. This framework allowed effective learning given only volumetric images and binary disease labels, thus enabling training from a large dataset of 6,631 un-annotated image volumes from 4,486 patients. When evaluated in a testing set of 2,163 volumes from 2,163 patients, our model distinguished emphysema with area under the receiver operating characteristic curve (AUC) of .83. This approach was found to outperform 2D convolutional neural networks (CNN) implemented with various multiple-instance learning schemes (AUC=0.69-0.76) and a 3D CNN (AUC=.77).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1812.01087](http://arxiv.org/abs/1812.01087)

##### PDF
[http://arxiv.org/pdf/1812.01087](http://arxiv.org/pdf/1812.01087)

