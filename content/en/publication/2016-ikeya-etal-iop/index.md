---
title: Protein NMR structure refinement based on Bayesian inference
date: '2016-01-01'
draft: false
publishDate: '2021-05-04T01:16:44.702924Z'
authors:
- Teppei Ikeya
- Shiro Ikeda
- Takanori Kigawa
- Yutaka Ito
- Peter Güntert
publication_types:
- '2'
abstract: Nuclear Magnetic Resonance (NMR) spectroscopy is a tool to investigate threedimensional (3D) structures and dynamics of biomacromolecules at atomic resolution in solution or more natural environments such as living cells. Since NMR data are principally only spectra with peak signals, it is required to properly deduce structural information from the sparse experimental data with their imperfections and uncertainty, and to visualize 3D conformations by NMR structure calculation. In order to efficiently analyse the data, Rieping et al. proposed a new structure calculation method based on Bayes' theorem. We implemented a similar approach into the program CYANA with some modifications. It allows us to handle automatic NOE cross peak assignments in unambiguous and ambiguous usages, and to create a prior distribution based on a physical force field with the generalized Born implicit water model. The sampling scheme for obtaining the posterior is performed by a hybrid Monte Carlo algorithm combined with Markov chain Monte Carlo (MCMC) by the Gibbs sampler, and molecular dynamics simulation (MD) for obtaining a canonical ensemble of conformations. Since it is not trivial to search the entire function space particularly for exploring the conformational prior due to the extraordinarily large conformation space of proteins, the replica exchange method is performed, in which several MCMC calculations with different temperatures run in parallel as replicas. It is shown with simulated data or randomly deleted experimental peaks that the new structure calculation method can provide accurate structures even with less peaks, especially compared with the conventional method. In particular, it dramatically improves in-cell structures of the proteins GB1 and TTHA1718 using exclusively information obtained in living Escherichia coli (E. coli) cells.
featured: false
publication: '*Journal of Physics: Conference Series*'
doi: 10.1088/1742-6596/699/1/012005
tags:
- '"NMR spectroscopy"'
---
