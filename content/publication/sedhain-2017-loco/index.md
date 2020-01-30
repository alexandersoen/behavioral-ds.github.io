---
title: "Low-rank linear cold-start recommendation from social data"
date: 2017-01-01
publishDate: 2019-12-29T23:55:04.493141Z
authors: ["Suvash Sedhain", "Aditya Krishna Menon", "Scott Sanner", "Lexing Xie", "Darius Braziunas"]
publication_types: ["1"]
abstract: "The cold-start problem involves recommendation of content to new users of a system, for whom there is no historical preference information available. This proves a challenge for collaborative filtering algorithms that inherently rely on such information. Recent work has shown that social metadata, such as users' friend groups and page likes, can strongly mitigate the problem. However, such approaches either lack an interpretation as optimising some principled objective, involve iterative non-convex optimisation with limited scalability, or require tuning several hyperparameters. In this paper, we first show how three popular cold-start models are special cases of a linear content-based model, with implicit constraints on the weights. Leveraging this insight, we propose Loco, a new model for cold-start recommendation based on three ingredients: (a) linear regression to learn an optimal weighting of social signals for preferences, (b) a low-rank parametrisation of the weights to overcome the high dimensionality common in social data, and (c) scalable learning of such low-rank weights using randomised SVD. Experiments on four real-world datasets show that Loco yields significant improvements over state-of-the-art cold-start recommenders that exploit high-dimensional social network metadata."
featured: false
publication: "*AAAI Conference on Artificial Intelligence (AAAI)*"
---
