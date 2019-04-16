---
layout: post
title: "Resource-Constrained Simultaneous Detection and Labeling of Objects in High-Resolution Satellite Images"
date: 2018-10-23 22:19:09
categories: arXiv_CV
tags: arXiv_CV Object_Detection CNN Inference Classification Detection
author: Gilbert Rotich, Rodrigo Minetto, Sudeep Sarkar
mathjax: true
---

* content
{:toc}

##### Abstract
We describe a strategy for detection and classification of man-made objects in large high-resolution satellite photos under computational resource constraints. We detect and classify candidate objects by using five pipelines of convolutional neural network processing (CNN), run in parallel. Each pipeline has its own unique strategy for fine tunning parameters, proposal region filtering, and dealing with image scales. The conflicting region proposals are merged based on region confidence and not just based on overlap areas, which improves the quality of the final bounding-box regions selected. We demonstrate this strategy using the recent xView challenge, which is a complex benchmark with more than 1,100 high-resolution images, spanning 800,000 aerial objects around the world covering a total area of 1,400 square kilometers at 0.3 meter ground sample distance. To tackle the resource-constrained problem posed by the xView challenge, where inferences are restricted to be on CPU with 8GB memory limit, we used lightweight CNN's trained with the single shot detector algorithm. Our approach was competitive on sequestered sets; it was ranked third.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.10110](https://arxiv.org/abs/1810.10110)

##### PDF
[https://arxiv.org/pdf/1810.10110](https://arxiv.org/pdf/1810.10110)

