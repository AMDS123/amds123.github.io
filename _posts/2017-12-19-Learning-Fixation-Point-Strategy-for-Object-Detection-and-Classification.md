---
layout: post
title: "Learning Fixation Point Strategy for Object Detection and Classification"
date: 2017-12-19 12:28:01
categories: arXiv_CV
tags: arXiv_CV Object_Detection Attention Classification Detection
author: Jie Lyu, Zejian Yuan, Dapeng Chen
mathjax: true
---

* content
{:toc}

##### Abstract
We propose a novel recurrent attentional structure to localize and recognize objects jointly. The network can learn to extract a sequence of local observations with detailed appearance and rough context, instead of sliding windows or convolutions on the entire image. Meanwhile, those observations are fused to complete detection and classification tasks. On training, we present a hybrid loss function to learn the parameters of the multi-task network end-to-end. Particularly, the combination of stochastic and object-awareness strategy, named SA, can select more abundant context and ensure the last fixation close to the object. In addition, we build a real-world dataset to verify the capacity of our method in detecting the object of interest including those small ones. Our method can predict a precise bounding box on an image, and achieve high speed on large images without pooling operations. Experimental results indicate that the proposed method can mine effective context by several local observations. Moreover, the precision and speed are easily improved by changing the number of recurrent steps. Finally, we will open the source code of our proposed approach.

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1712.06897](https://arxiv.org/abs/1712.06897)

##### PDF
[https://arxiv.org/pdf/1712.06897](https://arxiv.org/pdf/1712.06897)

