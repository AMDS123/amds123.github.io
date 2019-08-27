---
layout: post
title: "Depth-AGMNet: an Atrous Granular Multiscale Stereo Network Based on Depth Edge Auxiliary Task"
date: 2019-08-25 15:39:33
categories: arXiv_CV
tags: arXiv_CV CNN
author: Weida Yang
mathjax: true
---

* content
{:toc}

##### Abstract
Recently, end-to-end convolutional neural networks have achieved remarkable success in stereo estimation tasks. It is still a valuable but hard problem to find the correct correspondence for the ill-posed regions, such as texture-less areas, edge details, and small objects. Based on the above questions, this paper proposes Dedge-AGMNet to alleviate it in different methods. First, we present the multi-task network composes of a depth-edge auxiliary network and disparity estimation network.To fuse the information of the ancillary system effectively, we design Dedge-SPP to embed the depth edge contours. Besides, On the supervised and unsupervised tasks of the depth edge, the corresponding loss function is constructed for depth edge constraints. Second, we design the AGM module, which utilized the fusion of internal fine-grained feature and stacking convolution layers within a single layer, combining with the dilated convolution and parallel structure reasonably. It is beneficial to provide dense -scale receptive fields and potential correspondence. The results show that for the unsupervised task of depth edge, the network can optimize the edge effectively. Our proposed approach shows accurate disparity estimates and achieves state-of-the-art performances on Sceneflow, KITTI2012, and KITTI2015 benchmarks datasets.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1908.09346](http://arxiv.org/abs/1908.09346)

##### PDF
[http://arxiv.org/pdf/1908.09346](http://arxiv.org/pdf/1908.09346)

