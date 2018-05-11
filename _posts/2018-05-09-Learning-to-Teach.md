---
layout: post
title: "Learning to Teach"
date: 2018-05-09 04:41:26
categories: arXiv_AI
tags: arXiv_AI Knowledge Attention Reinforcement_Learning CNN Image_Classification Optimization RNN Classification
author: Yang Fan, Fei Tian, Tao Qin, Xiang-Yang Li, Tie-Yan Liu
mathjax: true
---

* content
{:toc}

##### Abstract
Teaching plays a very important role in our society, by spreading human knowledge and educating our next generations. A good teacher will select appropriate teaching materials, impact suitable methodologies, and set up targeted examinations, according to the learning behaviors of the students. In the field of artificial intelligence, however, one has not fully explored the role of teaching, and pays most attention to machine \emph{learning}. In this paper, we argue that equal attention, if not more, should be paid to teaching, and furthermore, an optimization framework (instead of heuristics) should be used to obtain good teaching strategies. We call this approach `learning to teach'. In the approach, two intelligent agents interact with each other: a student model (which corresponds to the learner in traditional machine learning algorithms), and a teacher model (which determines the appropriate data, loss function, and hypothesis space to facilitate the training of the student model). The teacher model leverages the feedback from the student model to optimize its own teaching strategies by means of reinforcement learning, so as to achieve teacher-student co-evolution. To demonstrate the practical value of our proposed approach, we take the training of deep neural networks (DNN) as an example, and show that by using the learning to teach techniques, we are able to use much less training data and fewer iterations to achieve almost the same accuracy for different kinds of DNN models (e.g., multi-layer perceptron, convolutional neural networks and recurrent neural networks) under various machine learning tasks (e.g., image classification and text understanding).

##### Abstract (translated by Google)
教学在我们的社会中起着非常重要的作用，通过传播人类的知识和教育我们的下一代。根据学生的学习行为，一位好的教师将选择合适的教材，影响合适的方法，并设定有针对性的考试。然而，在人工智能领域，人们还没有充分探索教学的作用，并且最关注机器学习。在本文中，我们认为应该对教学给予同等关注，如果不是更多，并且还应该使用优化框架（而不是启发式）来获得良好的教学策略。我们称这种方法为“学习教学”。在该方法中，两个智能代理彼此交互：学生模型（其对应于传统机器学习算法中的学习者）和教师模型（其确定适当的数据，损失函数和假设空间以促进学生模型）。教师模式利用学生模式的反馈，通过强化学习的方式优化自己的教学策略，实现师生共同进化。为了证明我们提出的方法的实际价值，我们以深度神经网络（DNN）的训练为例，并且表明通过使用学习来教授技术，我们能够使用更少的训练数据和更少的迭代来实现在各种机器学习任务（例如，图像分类和文本理解）下，对于不同类型的DNN模型（例如，多层感知器，卷积神经网络和递归神经网络）准确度几乎相同。

##### URL
[http://arxiv.org/abs/1805.03643](http://arxiv.org/abs/1805.03643)

##### PDF
[http://arxiv.org/pdf/1805.03643](http://arxiv.org/pdf/1805.03643)

