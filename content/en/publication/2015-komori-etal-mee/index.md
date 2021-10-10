---
title: An asymmetric logistic regression model for ecological data
date: '2015-10-01'
draft: false
publishDate: '2021-05-04T01:16:45.287155Z'
authors:
- Osamu Komori
- Shinto Eguchi
- Shiro Ikeda
- Hiroshi Okamura
- Momoko Ichinokawa
- Shinichiro Nakayama
publication_types:
- '2'
abstract: 1. Binary data are popular in ecological and environmental studies; however, due to various uncertainties and complexities present in data sets, the standard generalized linear model with a binomial error distribution often demonstrates insufficient predictive performance when analysing binary and proportional data.

  2. To address this difficulty, we propose an asymmetric logistic regression model that uses a new parameter to account for data complexity. We observe that this parameter controls the model's asymmetry and is important for adjusting the weights associated with observed data in order to improve model fitting. This model includes the ordinary logistic regression model as a special case. It is easily implemented using a slight modification of glm or glmer in statistical software R.

  3. Simulation studies suggest that our new approach outperforms a traditional approach in terms of both predictive accuracy and variable selection. In a case study involving fisheries data, we found that the annual catch amount had a greater impact on stock status prediction, and improved predictive capability was supported with a smaller AIC compared to a generalized linear model.

  4. In summary, our method can enhance the applicability of a generalized linear model to various ecological problems using a slight modification, and significantly improves model fitting and model selection.
featured: false
publication: '*Methods in Ecology and Evolution*'
doi: 10.1111/2041-210X.12473
tags:
- '"ecological data analysis"'
---
