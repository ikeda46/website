---
title: Denoising Weak Lensing Mass Maps with Deep Learning
date: '2019-08-01'
draft: false
publishDate: '2021-05-04T01:16:42.006699Z'
authors:
- Masato Shirasaki
- Naoki Yoshida
- Shiro Ikeda
publication_types:
- '2'
math: true
abstract: Weak gravitational lensing is a powerful probe of the large-scale cosmic matter distribution. Wide-field galaxy surveys allow us to generate the so-called weak lensing maps, but actual observations suffer from noise due to imperfect measurement of galaxy shape distortions and to the limited number density of the source galaxies. In this paper, we explore a deep-learning approach to reduce the noise. We develop an image-to-image translation method with conditional adversarial networks (CANs), which learn efficient mapping from an input noisy weak lensing map to the underlying noise field. We train the CANs using 30000 image pairs obtained from 1000 ray-tracing simulations of weak gravitational lensing. We show that the trained CANs reproduce the true one-point probability distribution function (PDF) of the noiseless lensing map with a bias less than 1 $\sigma$ on average, where $\sigma$ is the statistical error. We perform a Fisher analysis to make a forecast for cosmological parameter inference with the one-point lensing PDF. By our denoising method using CANs, the first derivative of the PDF with respect to the cosmic mean matter density and the amplitude of the primordial curvature perturbations becomes larger by $\sim$ 50 \%. This allows us to improve the cosmological constraints by $\sim$ 30\% $\sim$ 40\% using observational data from ongoing and upcoming galaxy imaging surveys.
featured: false
publication: '*Physical Review D*'
tags:
- '"cosmology"'
- '"deep learning"'
- '"weak lensing"'
- '"Subaru-HSC"'
- '"astronomy"'
doi: 10.1103/PhysRevD.100.043527
links:
- name: arXiv
  url: https://arxiv.org/abs/1812.05781
---
