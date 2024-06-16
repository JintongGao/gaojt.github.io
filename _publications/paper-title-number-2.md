---
title: "FP-Net: frequency-perception network with adversarial training for image manipulation localization"
collection: publications
permalink: /publication/paper-title-number-2
date: 2024-01-26
venue: 'MULTIMEDIA TOOLS AND APPLICATIONS'
paperurl: 'http://academicpages.github.io/files/paper2.pdf'
---

Mining the forged regions of digitally tampered images is one of the key research tasks for visual recognition. Although there are many algorithms investigating image manipulation localization, most approaches focus only on the semantic information of the spatial domain and ignore the frequency inconsistency between authentic and tampered regions. In addition, the generality and robustness of the models are severely affected by the different noise distributions of the training and test sets. To address these issues, we propose the frequency-perception network with adversarial training for image manipulation localization. Our method not only captures representation information for boundary artifact identification in the spatial domain but also separates low and high-frequency information in the frequency domain to acquire tampered cues. Specifically, the frequency separation sensing module enriches the local sensing range by separating multi-scale frequency domain features. It accurately identifies high-frequency noise features in the manipulated region and distinguishes low-frequency information. The global frequency attention module uses multiple sampling and convolution operations to interactively learn multi-scale feature information and integrate dual-domain frequency content to identify tampered physical locations. Adversarial training is employed to construct hard training adversarial samples based on adversarial attacks to avoid interference from unevenly distributed redundant noise information. Extensive experimental results show that our proposed method performs significantly better than the mainstream approach on five common standard datasets.
