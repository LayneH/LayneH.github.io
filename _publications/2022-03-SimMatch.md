---
title: "SimMatch: Semi-supervised Learning with Similarity Matching"
collection: publications
permalink: /publication/2022-03-SimMatch
excerpt: 'New algorithm for semi-supervised learning.'
date: 2022-03-01
venue: 'IEEE/CVF Conference on Computer Vision and Pattern Recognition'
paperurl: 'https://arxiv.org/pdf/2002.10319'
citation: 'Mingkai Zheng, Shan You, Lang Huang, Fei Wang, Chen Qian, Chang Xu (2022). &quot;SimMatch: Semi-supervised Learning with Similarity Matching; <i>IEEE/CVF Conference on Computer Vision and Pattern Recognition</i>.'
---

*Abstract*: Learning with few labeled data has been a longstanding problem in the computer vision and machine learning research community. In this paper, we introduced a new semi-supervised learning framework, SimMatch, which simultaneously considers semantic similarity and instance similarity. In SimMatch, the consistency regularization will be applied on both semantic-level and instance-level. The different augmented views of the same instance are encouraged to have the same class prediction and similar similarity relationship respected to other instances. Next, we instantiated a labeled memory buffer to fully leverage the ground truth labels on instance-level and bridge the gaps between the semantic and instance similarities. Finally, we proposed the unfolding and aggregation operation which allows these two similarities be isomorphically transformed with each other. In this way, the semantic and instance pseudo-labels can be mutually propagated to generate more high-quality and reliable matching targets. Extensive experimental results demonstrate that SimMatch improves the performance of semi-supervised learning tasks across different benchmark datasets and different settings. Notably, with 400 epochs of training, SimMatch achieves 67.2%, and 74.4% Top-1 Accuracy with 1% and 10% labeled examples on ImageNet, which significantly outperforms the baseline methods and is better than previous semi-supervised learning frameworks.

[\[Paper\]](http://arxiv.org/abs/2203.06915) [\[Code\]](https://github.com/KyleZheng1997/simmatch)