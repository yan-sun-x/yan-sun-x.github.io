---
title: "Deep orthogonal hypersphere compression for anomaly detection"
collection: publications
category: conferences
permalink: /publication/2024-01-16-dohc
excerpt: '**Anomaly Detection:** Introduces hypersphere-based methods (DOHSC, DO2HSC) for anomaly detection, including graph-level cases, offering compact decision regions and improved accuracy.'
date: 2024-01-16
venue: 'The Twelfth International Conference on Learning Representations (Spotlight)'
# slidesurl: 'http://academicpages.github.io/files/slides1.pdf'
paperurl: 'https://openreview.net/pdf?id=cJs4oE4m9Q'
citation: 'Zhang, Y., Sun, Y., Cai, J., & Fan, J. (2024). Deep orthogonal hypersphere compression for anomaly detection. In The Twelfth International Conference on Learning Representations.'
---

In this paper, we first propose a novel deep anomaly detection model that improves the original hypersphere learning through an orthogonal projection layer, which ensures that the training data distribution is consistent with the hypersphere hypothesis, thereby increasing the true positive rate and decreasing the false negative rate. Moreover, we propose a bi-hypersphere compression method to obtain a hyperspherical shell that yields a more compact decision region than a hyperball, which is demonstrated theoretically and numerically. The proposed methods are not confined to common datasets such as image and tabular data, but are also extended to a more challenging but promising scenario, graph-level anomaly detection, which learns graph representation with maximum mutual information between the substructure and global structure features while exploring orthogonal single- or bi-hypersphere anomaly decision boundaries. The numerical and visualization results on benchmark datasets demonstrate the superiority of our methods in comparison to many baselines and state-of-the-art methods.