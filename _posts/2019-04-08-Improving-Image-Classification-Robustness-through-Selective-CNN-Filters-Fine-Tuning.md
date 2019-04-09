---
layout: post
title: "Improving Image Classification Robustness through Selective CNN-Filters Fine-Tuning"
date: 2019-04-08 11:02:05
categories: arXiv_CV
tags: arXiv_CV Image_Classification Transfer_Learning Classification
author: Alessandro Bianchi, Moreno Raimondo Vendra, Pavlos Protopapas, Marco Brambilla
mathjax: true
---

* content
{:toc}

##### Abstract
Image quality plays a big role in CNN-based image classification performance. Fine-tuning the network with distorted samples may be too costly for large networks. To solve this issue, we propose a transfer learning approach optimized to keep into account that in each layer of a CNN some filters are more susceptible to image distortion than others. Our method identifies the most susceptible filters and applies retraining only to the filters that show the highest activation maps distance between clean and distorted images. Filters are ranked using the Borda count election method and then only the most affected filters are fine-tuned. This significantly reduces the number of parameters to retrain. We evaluate this approach on the CIFAR-10 and CIFAR-100 datasets, testing it on two different models and two different types of distortion. Results show that the proposed transfer learning technique recovers most of the lost performance due to input data distortion, at a considerably faster pace with respect to existing methods, thanks to the reduced number of parameters to fine-tune. When few noisy samples are provided for training, our filter-level fine tuning performs particularly well, also outperforming state of the art layer-level transfer learning approaches.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1904.03949](http://arxiv.org/abs/1904.03949)

##### PDF
[http://arxiv.org/pdf/1904.03949](http://arxiv.org/pdf/1904.03949)

