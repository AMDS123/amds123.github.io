---
layout: post
title: "TRk-CNN: Transferable Ranking-CNN for image classification of glaucoma, glaucoma suspect, and normal eyes"
date: 2019-05-16 02:45:04
categories: arXiv_CV
tags: arXiv_CV Survey CNN Image_Classification Classification Prediction Relation
author: Tae Joon Jun, Youngsub Eom, Dohyeun Kim, Cherry Kim, Ji-Hye Park, Hoang Minh Nguyen, Daeyoung Kim
mathjax: true
---

* content
{:toc}

##### Abstract
In this paper, we proposed Transferable Ranking Convolutional Neural Network (TRk-CNN) that can be effectively applied when the classes of images to be classified show a high correlation with each other. The multi-class classification method based on the softmax function, which is generally used, is not effective in this case because the inter-class relationship is ignored. Although there is a Ranking-CNN that takes into account the ordinal classes, it cannot reflect the inter-class relationship to the final prediction. TRk-CNN, on the other hand, combines the weights of the primitive classification model to reflect the inter-class information to the final classification phase. We evaluated TRk-CNN in glaucoma image dataset that was labeled into three classes: normal, glaucoma suspect, and glaucoma eyes. Based on the literature we surveyed, this study is the first to classify three status of glaucoma fundus image dataset into three different classes. We compared the evaluation results of TRk-CNN with Ranking-CNN (Rk-CNN) and multi-class CNN (MC-CNN) using the DenseNet as the backbone CNN model. As a result, TRk-CNN achieved an average accuracy of 92.96%, specificity of 93.33%, sensitivity for glaucoma suspect of 95.12% and sensitivity for glaucoma of 93.98%. Based on average accuracy, TRk-CNN is 8.04% and 9.54% higher than Rk-CNN and MC-CNN and surprisingly 26.83% higher for sensitivity for suspicious than multi-class CNN. Our TRk-CNN is expected to be effectively applied to the medical image classification problem where the disease state is continuous and increases in the positive class direction.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1905.06509](http://arxiv.org/abs/1905.06509)

##### PDF
[http://arxiv.org/pdf/1905.06509](http://arxiv.org/pdf/1905.06509)

