---
layout: post
title: "Deep Learning for Domain Adaption: Engagement Recognition"
date: 2018-08-07 12:38:20
categories: arXiv_CV
tags: arXiv_CV Face Classification Deep_Learning Recognition
author: Omid Mohamad Nezami, Len Hamey, Deborah Richards, Mark Dras
mathjax: true
---

* content
{:toc}

##### Abstract
Engagement is a key indicator of the quality of learning experience, and one that plays a major role in developing intelligent educational interfaces. Any such interface requires the ability to recognise the level of engagement in order to respond appropriately; however, there is very little existing data to learn from, and new data is expensive and difficult to acquire. This paper presents a deep learning model to improve engagement recognition from face images captured `in the wild' that overcomes the data sparsity challenge by pre-training on readily available basic facial expression data, before training on specialised engagement data. In the first of two steps, a state-of-the-art facial expression recognition model is trained to provide a rich face representation using deep learning. In the second step, we use the model's weights to initialize our deep learning based model to recognize engagement; we term this the Transfer model. We train the model on our new engagement recognition (ER) dataset with 4627 engaged and disengaged samples. We find that our Transfer architecture outperforms standard deep learning architectures that we apply for the first time to engagement recognition, as well as approaches using HOG features and SVMs. The model achieves a classification accuracy of 72.38%, which is 6.1% better than the best baseline model on the test set of the ER dataset. Using the F1 measure and the area under the ROC curve, our Transfer model achieves 73.90% and 73.74%, exceeding the best baseline model by 3.49% and 5.33% respectively.

##### Abstract (translated by Google)
参与度是学习体验质量的关键指标，也是开发智能教育界面的重要指标。任何此类界面都需要能够识别参与程度，以便做出适当的反应;但是，现有数据很少可以学习，新数据昂贵且难以获取。本文提出了一种深度学习模型，通过在专业参与数据培训之前，通过对现有基本面部表情数据进行预训练来克服数据稀疏性挑战，从而提高在野外捕获的面部图像的参与识别。在两个步骤的第一步中，训练最先进的面部表情识别模型以使用深度学习提供丰富的面部表示。在第二步中，我们使用模型的权重来初始化我们基于深度学习的模型以识别参与度;我们称之为转移模型。我们在新的参与识别（ER）数据集上训练模型，其中包含4627个已接合和脱离的样本。我们发现，我们的Transfer架构优于我们首次应用于参与识别的标准深度学习架构，以及使用HOG功能和SVM的方法。该模型的分类准确率为72.38％，比ER数据集测试集上的最佳基线模型好6.1％。使用F1测量和ROC曲线下面积，我们的Transfer模型分别达到73.90％和73.74％，超过最佳基线模型分别为3.49％和5.33％。

##### URL
[http://arxiv.org/abs/1808.02324](http://arxiv.org/abs/1808.02324)

##### PDF
[http://arxiv.org/pdf/1808.02324](http://arxiv.org/pdf/1808.02324)

