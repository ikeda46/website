---
title: Independent Component Analysis for Noisy Data --MEG data analysis
date: '2000-12-01'
draft: false
publishDate: '2021-05-04T01:16:49.636949Z'
authors:
- Shiro Ikeda
- Keisuke Toyama
publication_types:
- '2'
abstract: 'Independent component analysis (ICA) is a new, simple and powerful idea for analyzing multi-variant data. One of the successful applications is neurobiological data analysis such as electroencephalography (EEG), magnetic resonance imaging (MRI), and magnetoencephalography (MEG). However, many problems remain. In most cases, neurobiological data contain a lot of sensor noise, and the number of independent components is unknown. In this article, we discuss an approach to separate noise-contaminated data without knowing the number of independent components. A well-known two stage approach to ICA is to pre-process the data by principal component analysis (PCA), and then the necessary rotation matrix is estimated. Since PCA does not work well for noisy data, we implement a factor analysis model for pre-processing. In the new pre-processing, the number of sources and the amount of sensor noise are estimated. After the pre-processing, the rotation matrix is estimated using an ICA method. Through the experiments with MEG data, we show this approach is effective.'
featured: true
publication: '*Neural Networks*'
doi: 10.1016/S0893-6080(00)00071-X
---
