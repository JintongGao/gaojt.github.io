---
title: "FedNPC: Stochastic Noise-driven Post-hoc Classifier Calibration Method for Federated Long-tailed Learning"
collection: publications
venue: 'CVPR Findings'
permalink: /publication/paper-title-number-5
date: 2026-05-07
paperurl: 'https://openreview.net/pdf?id=4befwY9BMr'
---

Federated long-tailed learning (Fed-LT) simultaneously tackles data heterogeneity across clients and global long-tailed distribution challenges. Existing approaches often depend on auxiliary datasets, gradients, or statistical information, which not only increase communication overhead but also introduce significant privacy leakage risks. To address these issues, we first conduct a systematic empirical study of the classifier bias under imbalanced data. We observe that the norm imbalance problem is substantially more severe in Fed-LT than in the centralized LT setting. Motivated by this observation, we propose FedNPC (stochastic Noise-driven Post-hoc classifier Calibration), a novel data-free post-processing calibration method for Fed-LT, using a virtual, balanced dataset. Furthermore, we provide theoretical insights showing that isotropic noise can effectively mitigate classifier norm imbalance. Extensive experiments on multiple Fed-LT benchmarks demonstrate the superior performance and generalization ability of FedNPC. Our code is available at https://github.com/JintongGao/FedNPC.
