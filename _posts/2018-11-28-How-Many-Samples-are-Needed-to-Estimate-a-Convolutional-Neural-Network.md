---
layout: post
title: "How Many Samples are Needed to Estimate a Convolutional Neural Network?"
date: 2018-11-28 04:18:24
categories: arXiv_AI
tags: arXiv_AI CNN Prediction
author: Simon S. Du, Yining Wang, Xiyu Zhai, Sivaraman Balakrishnan, Ruslan Salakhutdinov, Aarti Singh
mathjax: true
---

* content
{:toc}

##### Abstract
A widespread folklore for explaining the success of Convolutional Neural Networks (CNNs) is that CNNs use a more compact representation than the Fully-connected Neural Network (FNN) and thus require fewer training samples to accurately estimate their parameters. We initiate the study of rigorously characterizing the sample complexity of estimating CNNs. We show that for an $m$-dimensional convolutional filter with linear activation acting on a $d$-dimensional input, the sample complexity of achieving population prediction error of $\epsilon$ is $\widetilde{O}(m/\epsilon^2)$ whereas the sample-complexity for its FNN counterpart is lower bounded by $\Omega(d/\epsilon^2)$ samples. Since, in typical settings $m \ll d$, this result demonstrates the advantage of using a CNN. We further consider the sample complexity of estimating a one-hidden-layer CNN with linear activation where both the $m$-dimensional convolutional filter and the $r$-dimensional output weights are unknown. For this model, we show that the sample complexity is $\widetilde{O}\left((m+r)/\epsilon^2\right)$ when the ratio between the stride size and the filter size is a constant. For both models, we also present lower bounds showing our sample complexities are tight up to logarithmic factors. Our main tools for deriving these results are a localized empirical process analysis and a new lemma characterizing the convolutional structure. We believe that these tools may inspire further developments in understanding CNNs.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1805.07883](http://arxiv.org/abs/1805.07883)

##### PDF
[http://arxiv.org/pdf/1805.07883](http://arxiv.org/pdf/1805.07883)

