---
layout: post
title: "Floors are Flat: Leveraging Semantics for Real-Time Surface Normal Prediction"
date: 2019-06-16 23:01:32
categories: arXiv_CV
tags: arXiv_CV Face Deep_Learning Prediction
author: Steven Hickson, Karthik Raveendran, Alireza Fathi, Kevin Murphy, Irfan Essa
mathjax: true
---

* content
{:toc}

##### Abstract
We propose 4 insights that help to significantly improve the performance of deep learning models that predict surface normals and semantic labels from a single RGB image. These insights are: (1) denoise the "ground truth" surface normals in the training set to ensure consistency with the semantic labels; (2) concurrently train on a mix of real and synthetic data, instead of pretraining on synthetic and finetuning on real; (3) jointly predict normals and semantics using a shared model, but only backpropagate errors on pixels that have valid training labels; (4) slim down the model and use grayscale instead of color inputs. Despite the simplicity of these steps, we demonstrate consistently improved results on several datasets, using a model that runs at 12 fps on a standard mobile phone.

##### Abstract (translated by Google)


##### URL
[http://arxiv.org/abs/1906.06792](http://arxiv.org/abs/1906.06792)

##### PDF
[http://arxiv.org/pdf/1906.06792](http://arxiv.org/pdf/1906.06792)

