---
layout: post
title: "Benchmarking unsupervised near-duplicate image detection"
date: 2019-07-03 09:08:47
categories: arXiv_CV
tags: arXiv_CV Image_Retrieval Knowledge CNN Classification Deep_Learning Detection
author: Lia Morra, Fabrizio Lamberti
mathjax: true
---

* content
{:toc}

##### Abstract
Unsupervised near-duplicate detection has many practical applications ranging from social media analysis and web-scale retrieval, to digital image forensics. It entails running a threshold-limited query on a set of descriptors extracted from the images, with the goal of identifying all possible near-duplicates, while limiting the false positives due to visually similar images. Since the rate of false alarms grows with the dataset size, a very high specificity is thus required, up to $1 - 10^{-9}$ for realistic use cases; this important requirement, however, is often overlooked in literature. In recent years, descriptors based on deep convolutional neural networks have matched or surpassed traditional feature extraction methods in content-based image retrieval tasks. To the best of our knowledge, ours is the first attempt to establish the performance range of deep learning-based descriptors for unsupervised near-duplicate detection on a range of datasets, encompassing a broad spectrum of near-duplicate definitions. We leverage both established and new benchmarks, such as the Mir-Flick Near-Duplicate (MFND) dataset, in which a known ground truth is provided for all possible pairs over a general, large scale image collection. To compare the specificity of different descriptors, we reduce the problem of unsupervised detection to that of binary classification of near-duplicate vs. not-near-duplicate images. The latter can be conveniently characterized using Receiver Operating Curve (ROC). Our findings in general favor the choice of fine-tuning deep convolutional networks, as opposed to using off-the-shelf features, but differences at high specificity settings depend on the dataset and are often small. The best performance was observed on the MFND benchmark, achieving 96\% sensitivity at a false positive rate of $1.43 \times 10^{-6}$.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1907.02821](http://arxiv.org/abs/1907.02821)

##### PDF
[http://arxiv.org/pdf/1907.02821](http://arxiv.org/pdf/1907.02821)

