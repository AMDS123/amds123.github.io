---
layout: post
title: "Unsupervised Identification of Disease Marker Candidates in Retinal OCT Imaging Data"
date: 2018-10-31 16:55:46
categories: arXiv_CV
tags: arXiv_CV Classification Detection
author: Philipp Seeb&#xf6;ck, Sebastian M. Waldstein, Sophie Klimscha, Hrvoje Bogunovic, Thomas Schlegl, Bianca S. Gerendas, Ren&#xe9; Donner, Ursula Schmidt-Erfurth, Georg Langs
mathjax: true
---

* content
{:toc}

##### Abstract
The identification and quantification of markers in medical images is critical for diagnosis, prognosis, and disease management. Supervised machine learning enables the detection and exploitation of findings that are known a priori after annotation of training examples by experts. However, supervision does not scale well, due to the amount of necessary training examples, and the limitation of the marker vocabulary to known entities. In this proof-of-concept study, we propose unsupervised identification of anomalies as candidates for markers in retinal Optical Coherence Tomography (OCT) imaging data without a constraint to a priori definitions. We identify and categorize marker candidates occurring frequently in the data, and demonstrate that these markers show predictive value in the task of detecting disease. A careful qualitative analysis of the identified data driven markers reveals how their quantifiable occurrence aligns with our current understanding of disease course, in early- and late age-related macular degeneration (AMD) patients. A multi-scale deep denoising autoencoder is trained on healthy images, and a one-class support vector machine identifies anomalies in new data. Clustering in the anomalies identifies stable categories. Using these markers to classify healthy-, early AMD- and late AMD cases yields an accuracy of 81.40%. In a second binary classification experiment on a publicly available data set (healthy vs. intermediate AMD) the model achieves an area under the ROC curve of 0.944.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1810.13404](http://arxiv.org/abs/1810.13404)

##### PDF
[http://arxiv.org/pdf/1810.13404](http://arxiv.org/pdf/1810.13404)

