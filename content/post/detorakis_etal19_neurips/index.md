---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "New Article NeurIPS 2019 on Stochastic Neural Networks"
subtitle: "Inherent Weight Normalization in Stochastic Neural Networks"
summary: "Inherent Weight Normalization in Stochastic Neural Networks"
authors: []
tags: []
categories: []
date: 2020-03-13T17:21:59-07:00
lastmod: 2020-03-13T17:21:59-07:00
featured: false
draft: false

# Featured image
image:
  caption: "New Article NeurIPS 2019 on Stochastic Neural Networks"
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: ['ssm']
---
Multiplicative stochasticity such as Dropout improves the robustness and gener- alizability deep neural networks. Here, we further demonstrate that always-on multiplicative stochasticity combined with simple threshold neurons provide a suf- ficient substrate for deep learning machines. We call such models Neural Sampling Machines (NSM). We find that the probability of activation of the NSM exhibits a self-normalizing property that mirrors Weight Normalization, a previously studied mechanism that fulfills many of the features of Batch Normalization in an online fashion. The normalization of activities during training speeds up convergence by preventing internal covariate shift caused by changes in the distribution of inputs. The always-on stochasticity of the NSM confers the following advantages: the network is identical in the inference and learning phases, making the NSM a suitable substrate for continual learning, it can exploit stochasticity inherent to a physical substrate such as analog non-volatile memories for in memory computing, and it is suitable for Monte Carlo sampling, while requiring almost exclusively addition and comparison operations. We demonstrate NSMs on standard classification benchmarks (MNIST and CIFAR) and event-based classification benchmarks (N-MNIST and DVS Gestures). Our results show that NSMs perform comparably or better than conventional artificial neural networks with the same architecture. 

See <a href=../../publication/detorakis-etal-19-a/ >publication here </a>.
