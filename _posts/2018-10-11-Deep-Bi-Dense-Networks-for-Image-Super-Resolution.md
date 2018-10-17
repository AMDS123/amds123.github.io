---
layout: post
title: "Deep Bi-Dense Networks for Image Super-Resolution"
date: 2018-10-11 07:34:39
categories: arXiv_CV
tags: arXiv_CV Super_Resolution CNN
author: Yucheng Wang, Jialiang Shen, Jian Zhang
mathjax: true
---

* content
{:toc}

##### Abstract
This paper proposes Deep Bi-Dense Networks (DBDN) for single image super-resolution. Our approach extends previous intra-block dense connection approaches by including novel inter-block dense connections. In this way, feature information propagates from a single dense block to all subsequent blocks, instead of to a single successor. To build a DBDN, we firstly construct intra-dense blocks, which extract and compress abundant local features via densely connected convolutional layers and compression layers for further feature learning. Then, we use an inter-block dense net to connect intra-dense blocks, which allow each intra-dense block propagates its own local features to all successors. Additionally, our bi-dense construction connects each block to the output, alleviating the vanishing gradient problems in training. The evaluation of our proposed method on five benchmark datasets shows that our DBDN outperforms the state of the art in SISR with a moderate number of network parameters.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1810.04873](https://arxiv.org/abs/1810.04873)

##### PDF
[https://arxiv.org/pdf/1810.04873](https://arxiv.org/pdf/1810.04873)

