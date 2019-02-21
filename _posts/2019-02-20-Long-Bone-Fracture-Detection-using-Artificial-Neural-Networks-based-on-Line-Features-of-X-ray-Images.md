---
layout: post
title: "Long-Bone Fracture Detection using Artificial Neural Networks based on Line Features of X-ray Images"
date: 2019-02-20 08:51:41
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Alice Yi Yang, Ling Cheng
mathjax: true
---

* content
{:toc}

##### Abstract
Two line-based fracture detection scheme are developed and discussed, namely Standard line-based fracture detection and Adaptive Differential Parameter Optimized (ADPO) line-based fracture detection. The purpose for the two line-based fracture detection schemes is to detect fractured lines from X-ray images using extracted features based on recognised patterns to differentiate fractured lines from non-fractured lines. The difference between the two schemes is the detection of detailed lines. The ADPO scheme optimizes the parameters of the Probabilistic Hough Transform, such that granule lines within the fractured regions are detected, whereas the Standard scheme is unable to detect them. The lines are detected using the Probabilistic Hough Function, in which the detected lines are a representation of the image edge objects. The lines are given in the form of points, (x,y), which includes the starting and ending point. Based on the given line points, 13 features are extracted from each line, as a summary of line information. These features are used for fracture and non-fracture classification of the detected lines. The classification is carried out by the Artificial Neural Network (ANN). There are two evaluations that are employed to evaluate both the entirety of the system and the ANN. The Standard Scheme is capable of achieving an average accuracy of 74.25%, whilst the ADPO scheme achieved an average accuracy of 74.4%. The ADPO scheme is opted for over the Standard scheme, however it can be further improved with detected contours and its extracted features.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1902.07458](http://arxiv.org/abs/1902.07458)

##### PDF
[http://arxiv.org/pdf/1902.07458](http://arxiv.org/pdf/1902.07458)

