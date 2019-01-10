---
layout: post
title: "Presence-absence estimation in audio recordings of tropical frog communities"
date: 2019-01-08 20:08:42
categories: arXiv_SD
tags: arXiv_SD Object_Detection Classification Detection
author: Andr&#xe9;s Estrella Terneux, Dami&#xe1;n Nicolalde, Daniel Nicolalde, Andr&#xe9;s Merino-Viteri
mathjax: true
---

* content
{:toc}

##### Abstract
One non-invasive way to study frog communities is by analyzing long-term samples of acoustic material containing calls. This immense task has been optimized by the development of Machine Learning tools to extract ecological information. We explored a likelihood-ratio audio detector based on Gaussian mixture model classification of 10 frog species, and applied it to estimate presence-absence in audio recordings from an actual amphibian monitoring performed at Yasun\'i National Park in the Ecuadorian Amazonia. A modified filter-bank was used to extract 20 cepstral features that model the spectral content of frog calls. Experiments were carried out to investigate the hyperparameters and the minimum frog-call time needed to train an accurate GMM classifier. With 64 Gaussians and 12 seconds of training time, the classifier achieved an average weighted error rate of 0.9% on the 10-fold cross-validation for nine species classification, as compared to 3% with MFCC and 1.8% with PLP features. For testing, 10 GMMs were trained using all the available training-validation dataset to study 23.5 hours in 141, 10-minute long samples of unidentified real-world audio recorded at two frog communities in 2001 with analog equipment. To evaluate automatic presence-absence estimation, we characterized the audio samples with 10 binary variables each corresponding to a frog species, and manually labeled a sub-set of 18 samples using headphones. A recall of 87.5% and precision of 100% with average accuracy of 96.66% suggests good generalization ability of the algorithm, and provides evidence of the validity of this approach to study real-world audio recorded in a tropical acoustic environment. Finally, we applied the algorithm to the available corpus, and show its potentiality to gain insights into the temporal reproductive behavior of frogs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1901.02495](http://arxiv.org/abs/1901.02495)

##### PDF
[http://arxiv.org/pdf/1901.02495](http://arxiv.org/pdf/1901.02495)

