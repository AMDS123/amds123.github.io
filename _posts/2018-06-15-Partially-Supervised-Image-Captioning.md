---
layout: post
title: "Partially-Supervised Image Captioning"
date: 2018-06-15 14:52:40
categories: arXiv_CV
tags: arXiv_CV Image_Caption Object_Detection Caption RNN Detection
author: Peter Anderson, Stephen Gould, Mark Johnson
mathjax: true
---

* content
{:toc}

##### Abstract
Image captioning models are becoming increasingly successful at describing the content of images in restricted domains. However, if these models are to function in the wild - for example, as aids for the visually impaired - a much larger number and variety of visual concepts must be understood. In this work, we teach image captioning models new visual concepts with partial supervision, such as available from object detection and image label datasets. As these datasets contain text fragments rather than complete captions, we formulate this problem as learning from incomplete data. To flexibly characterize our uncertainty about the unobserved complete sequence, we represent each incomplete training sequence with its own finite state automaton encoding acceptable complete sequences. We then propose a novel algorithm for training sequence models, such as recurrent neural networks, on incomplete sequences specified in this manner. In the context of image captioning, our method lifts the restriction that previously required image captioning models to be trained on paired image-sentence corpora only, or otherwise required specialized model architectures to take advantage of alternative data modalities. Applying our approach to an existing neural captioning model, we achieve state of the art results on the novel object captioning task using the COCO dataset. We further show that we can train a captioning model to describe new visual concepts from the Open Images dataset while maintaining competitive COCO evaluation scores.

##### Abstract (translated by Google)
图像字幕模型在描述受限域中的图像内容方面越来越成功。然而，如果这些模型在野外发挥作用 - 例如，作为视障者的辅助手段 - 则必须了解更多数量和种类的视觉概念。在这项工作中，我们教授图像字幕模型新的视觉概念与部分监督，如可从物体检测和图像标签数据集。由于这些数据集包含文本片段而不是完整的标题，因此我们将此问题制定为从不完整数据中学习。为了灵活地表征我们对未观察到的完整序列的不确定性，我们使用自己的有限状态自动机来表示每个不完整的训练序列，其编码可接受的完整序列。然后，我们提出了一种用于以这种方式指定的不完整序列训练序列模型的新算法，例如递归神经网络。在图像字幕的背景下，我们的方法解除了先前只需要在配对的图像句子语料库上训练图像字幕模型的限制，或者需要专门的模型体系结构来利用替代数据模态。将我们的方法应用于现有的神经字幕模型，我们使用COCO数据集实现了新颖的对象字幕任务的最新成果。我们进一步表明，我们可以训练字幕模型来描述开放图像数据集中的新视觉概念，同时保持具有竞争力的COCO评估分数。

##### URL
[http://arxiv.org/abs/1806.06004](http://arxiv.org/abs/1806.06004)

##### PDF
[http://arxiv.org/pdf/1806.06004](http://arxiv.org/pdf/1806.06004)

