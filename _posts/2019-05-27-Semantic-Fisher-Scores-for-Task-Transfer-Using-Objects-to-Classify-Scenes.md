---
layout: post
title: "Semantic Fisher Scores for Task Transfer: Using Objects to Classify Scenes"
date: 2019-05-27 23:15:26
categories: arXiv_CV
tags: arXiv_CV Classification
author: Mandar Dixit, Yunsheng Li, Nuno Vasconcelos
mathjax: true
---

* content
{:toc}

##### Abstract
The transfer of a neural network (CNN) trained to recognize objects to the task of scene classification is considered. A Bag-of-Semantics (BoS) representation is first induced, by feeding scene image patches to the object CNN, and representing the scene image by the ensuing bag of posterior class probability vectors (semantic posteriors). The encoding of the BoS with a Fisher vector(FV) is then studied. A link is established between the FV of any probabilistic model and the Q-function of the expectation-maximization(EM) algorithm used to estimate its parameters by maximum likelihood. A network implementation of the MFA Fisher Score (MFA-FS), denoted as the MFAFSNet, is finally proposed to enable end-to-end training. Experiments with various object CNNs and datasets show that the approach has state-of-the-art transfer performance. Somewhat surprisingly, the scene classification results are superior to those of a CNN explicitly trained for scene classification, using a large scene dataset (Places). This suggests that holistic analysis is insufficient for scene classification. The modeling of local object semantics appears to be at least equally important. The two approaches are also shown to be strongly complementary, leading to very large scene classification gains when combined, and outperforming all previous scene classification approaches by a sizeable margin

##### Abstract (translated by Google)


##### URL
[https://arxiv.org/abs/1905.11539](https://arxiv.org/abs/1905.11539)

##### PDF
[https://arxiv.org/pdf/1905.11539](https://arxiv.org/pdf/1905.11539)

