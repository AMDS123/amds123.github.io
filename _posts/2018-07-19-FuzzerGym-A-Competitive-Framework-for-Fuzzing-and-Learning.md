---
layout: post
title: "FuzzerGym: A Competitive Framework for Fuzzing and Learning"
date: 2018-07-19 15:22:35
categories: arXiv_AI
tags: arXiv_AI Reinforcement_Learning Classification Detection
author: William Drozd, Michael D. Wagner
mathjax: true
---

* content
{:toc}

##### Abstract
Fuzzing is a commonly used technique designed to test software by automatically crafting program inputs. Currently, the most successful fuzzing algorithms emphasize simple, low-overhead strategies with the ability to efficiently monitor program state during execution. Through compile-time instrumentation, these approaches have access to numerous aspects of program state including coverage, data flow, and heterogeneous fault detection and classification. However, existing approaches utilize blind random mutation strategies when generating test inputs. We present a different approach that uses this state information to optimize mutation operators using reinforcement learning (RL). By integrating OpenAI Gym with libFuzzer we are able to simultaneously leverage advancements in reinforcement learning as well as fuzzing to achieve deeper coverage across several varied benchmarks. Our technique connects the rich, efficient program monitors provided by LLVM Santizers with a deep neural net to learn mutation selection strategies directly from the input data. The cross-language, asynchronous architecture we developed enables us to apply any OpenAI Gym compatible deep reinforcement learning algorithm to any fuzzing problem with minimal slowdown.

##### Abstract (translated by Google)
模糊测试是一种常用的技术，旨在通过自动制作程序输入来测试软件。目前，最成功的模糊算法强调简单，低开销的策略，能够在执行期间有效地监视程序状态。通过编译时仪器，这些方法可以访问程序状态的许多方面，包括覆盖范围，数据流和异构故障检测和分类。然而，现有方法在生成测试输入时利用盲随机变异策略。我们提出了一种不同的方法，使用这种状态信息来优化使用强化学习（RL）的变异算子。通过将OpenAI Gym与libFuzzer集成，我们能够同时利用强化学习的进步以及模糊测试来实现跨多个基准测试的更深层次的覆盖。我们的技术将LLVM Santizers提供的丰富，高效的程序监视器与深度神经网络连接起来，直接从输入数据中学习突变选择策略。我们开发的跨语言异步架构使我们能够将任何OpenAI Gym兼容的深度强化学习算法应用于任何模糊问题，并将速度降至最低。

##### URL
[http://arxiv.org/abs/1807.07490](http://arxiv.org/abs/1807.07490)

##### PDF
[http://arxiv.org/pdf/1807.07490](http://arxiv.org/pdf/1807.07490)

