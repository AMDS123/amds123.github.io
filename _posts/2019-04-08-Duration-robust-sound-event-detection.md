---
layout: post
title: "Duration robust sound event detection"
date: 2019-04-08 05:07:14
categories: arXiv_SD
tags: arXiv_SD CNN RNN Detection
author: Heinrich Dinkel, Kai Yu
mathjax: true
---

* content
{:toc}

##### Abstract
Task 4 of the Dcase2018 challenge demonstrated that substantially more research is needed for a real-world application of sound event detection. Analyzing the challenge results it can be seen that most successful models are biased towards predicting long (e.g., over 5s) utterances. This work aims to investigate the performance impact of fixed sized window median filter post-processing and advocate the use of double thresholding as a more robust and predictable post-processing method. Further, four different temporal subsampling methods within the CRNN framework are proposed: mean-max, alpha-mean-max, Lp-norm and convolutional. We show that for this task subsampling the temporal resolution by a neural network enhances the F1 score as well as onset and offset accuracies. Our best single model achieves 30.1% F1 on the evaluation set and the best fusion model 32.5%, outperforming the previously best attempt by 0.1% while maintaining robustness to short events.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03841](http://arxiv.org/abs/1904.03841)

##### PDF
[http://arxiv.org/pdf/1904.03841](http://arxiv.org/pdf/1904.03841)

