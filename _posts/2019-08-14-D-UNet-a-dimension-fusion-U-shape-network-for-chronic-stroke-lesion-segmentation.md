---
layout: post
title: "D-UNet: a dimension-fusion U shape network for chronic stroke lesion segmentation"
date: 2019-08-14 12:54:04
categories: arXiv_CV
tags: arXiv_CV Segmentation CNN
author: Yongjin Zhou, Weijian Huang, Pei Dong, Yong Xia, Shanshan Wang
mathjax: true
---

* content
{:toc}

##### Abstract
Assessing the location and extent of lesions caused by chronic stroke is critical for medical diagnosis, surgical planning, and prognosis. In recent years, with the rapid development of 2D and 3D convolutional neural networks (CNN), the encoder-decoder structure has shown great potential in the field of medical image segmentation. However, the 2D CNN ignores the 3D information of medical images, while the 3D CNN suffers from high computational resource demands. This paper proposes a new architecture called dimension-fusion-UNet (D-UNet), which combines 2D and 3D convolution innovatively in the encoding stage. The proposed architecture achieves a better segmentation performance than 2D networks, while requiring significantly less computation time in comparison to 3D networks. Furthermore, to alleviate the data imbalance issue between positive and negative samples for the network training, we propose a new loss function called Enhance Mixing Loss (EML). This function adds a weighted focal coefficient and combines two traditional loss functions. The proposed method has been tested on the ATLAS dataset and compared to three state-of-the-art methods. The results demonstrate that the proposed method achieves the best quality performance in terms of DSC = 0.5349+0.2763 and precision = 0.6331+0.295).

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.05104](http://arxiv.org/abs/1908.05104)

##### PDF
[http://arxiv.org/pdf/1908.05104](http://arxiv.org/pdf/1908.05104)

