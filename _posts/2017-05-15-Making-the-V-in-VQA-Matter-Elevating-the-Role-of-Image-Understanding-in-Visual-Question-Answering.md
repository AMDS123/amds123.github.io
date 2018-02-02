---
layout: post
title: "Making the V in VQA Matter: Elevating the Role of Image Understanding in Visual Question Answering"
date: 2017-05-15 17:58:49
categories: arXiv_CV
tags: arXiv_CV Image_Caption QA VQA
author: Yash Goyal, Tejas Khot, Douglas Summers-Stay, Dhruv Batra, Devi Parikh
mathjax: true
---

* content
{:toc}

##### Abstract
Problems at the intersection of vision and language are of significant importance both as challenging research questions and for the rich set of applications they enable. However, inherent structure in our world and bias in our language tend to be a simpler signal for learning than visual modalities, resulting in models that ignore visual information, leading to an inflated sense of their capability. We propose to counter these language priors for the task of Visual Question Answering (VQA) and make vision (the V in VQA) matter! Specifically, we balance the popular VQA dataset by collecting complementary images such that every question in our balanced dataset is associated with not just a single image, but rather a pair of similar images that result in two different answers to the question. Our dataset is by construction more balanced than the original VQA dataset and has approximately twice the number of image-question pairs. Our complete balanced dataset is publicly available at www.visualqa.org as part of the 2nd iteration of the Visual Question Answering Dataset and Challenge (VQA v2.0). We further benchmark a number of state-of-art VQA models on our balanced dataset. All models perform significantly worse on our balanced dataset, suggesting that these models have indeed learned to exploit language priors. This finding provides the first concrete empirical evidence for what seems to be a qualitative sense among practitioners. Finally, our data collection protocol for identifying complementary images enables us to develop a novel interpretable model, which in addition to providing an answer to the given (image, question) pair, also provides a counter-example based explanation. Specifically, it identifies an image that is similar to the original image, but it believes has a different answer to the same question. This can help in building trust for machines among their users.

##### Abstract (translated by Google)
视觉和语言的交叉问题对于具有挑战性的研究问题和丰富的应用程序都是非常重要的。然而，我们世界的固有结构和我们的语言中的偏见往往是一个比视觉形式更简单的学习信号，导致忽视视觉信息的模型，导致其能力的膨胀感。我们建议针对视觉问答（VQA）的任务对付这些语言的先验，并使视觉（VQA中的V）重要！具体而言，我们通过收集互补图像来平衡流行的VQA数据集，使得我们的平衡数据集中的每个问题不仅与单个图像相关联，而且与导致对该问题的两个不同答案的相似图像相关联。我们的数据集的结构比原始的VQA数据集更加平衡，大约有两个图像问题对的数量。我们完整的平衡数据集可以在www.visualqa.org上公开获取，作为视觉问答应答数据集和挑战（VQA v2.0）的第二次迭代的一部分。我们在平衡的数据集上进一步对许多最先进的VQA模型进行基准测试。所有的模型在我们的平衡数据集上都表现得更差，这表明这些模型确实学会了利用语言先验。这一发现提供了第一个具体的经验证据，在实践中似乎是一种质的意义。最后，我们用于识别补充图像的数据收集协议使我们能够开发一种新颖的可解释模型，除了提供给定（图像，问题）对的答案之外，还提供了基于反例的解释。具体来说，它确定了一个与原始图像相似的图像，但它相信对于同一个问题有不同的答案。这可以帮助在用户之间建立对机器的信任。

##### URL
[https://arxiv.org/abs/1612.00837](https://arxiv.org/abs/1612.00837)

##### PDF
[https://arxiv.org/pdf/1612.00837](https://arxiv.org/pdf/1612.00837)

