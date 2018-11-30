---
layout: post
title: "Progressive Recurrent Learning for Visual Recognition"
date: 2018-11-29 10:16:32
categories: arXiv_CV
tags: arXiv_CV Segmentation Semantic_Segmentation Prediction Recognition
author: Xutong Ren, Lingxi Xie, Chen Wei, Siyuan Qiao, Chi Su, Jiaying Liu, Alan L. Yuille
mathjax: true
---

* content
{:toc}

##### Abstract
Computer vision is difficult, partly because the mathematical function connecting input and output data is often complex, fuzzy and thus hard to learn. A currently popular solution is to design a deep neural network and optimize it on a large-scale dataset. However, as the number of parameters increases, the generalization ability is often not guaranteed, e.g., the model can over-fit due to the limited amount of training data, or fail to converge because the desired function is too difficult to learn. This paper presents an effective framework named progressive recurrent learning (PRL). The core idea is similar to curriculum learning which gradually increases the difficulty of training data. We generalize it to a wide range of vision problems that were previously considered less proper to apply curriculum learning. PRL starts with inserting a recurrent prediction scheme, based on the motivation of feeding the prediction of a vision model to the same model iteratively, so that the auxiliary cues contained in it can be exploited to improve the quality of itself. In order to better optimize this framework, we start with providing perfect prediction, i.e., ground-truth, to the second stage, but gradually replace it with the prediction of the first stage. In the final status, the ground-truth information is not needed any more, so that the entire model works on the real data distribution as in the testing process. We apply PRL to two challenging visual recognition tasks, namely, object localization and semantic segmentation, and demonstrate consistent accuracy gain compared to the baseline training strategy, especially in the scenarios of more difficult vision tasks.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1811.12047](http://arxiv.org/abs/1811.12047)

##### PDF
[http://arxiv.org/pdf/1811.12047](http://arxiv.org/pdf/1811.12047)

