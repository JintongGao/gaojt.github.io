---
title: "Enhancing Minority Classes by Mixing: An Adaptative Optimal Transport Approach for Long-tailed Classification"
collection: publications
permalink: /publication/paper-title-number-3
date: 2023-09-22
venue: 'NeurIPS'
paperurl: 'https://openreview.net/pdf?id=M7FQpIdo0X'
---

Real-world data usually confronts severe class-imbalance problems, where several majority classes have a significantly larger presence in the training set than minority classes. One effective solution is using mixup-based methods to generate synthetic samples to enhance the presence of minority classes. Previous approaches mix the background images from the majority classes and foreground images from the minority classes in a random manner, which ignores the sample-level semantic similarity, possibly resulting in less reasonable or less useful images. In this work, we propose an adaptive image-mixing method based on optimal transport (OT) to incorporate both class-level and sample-level information, which is able to generate semantically reasonable and meaningful mixed images for minority classes. Due to its flexibility, our method can be combined with existing long-tailed classification methods to enhance their performance and it can also serve as a general data augmentation method for balanced datasets. Extensive experiments indicate that our method achieves effective performance for long-tailed classification tasks.
