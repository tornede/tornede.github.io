---
title: "Coevolution of Remaining Useful Lifetime Estimation Pipelines for Automated Predictive Maintenance"
author: "**Tanja Tornede**, Alexander Tornede, Marcel Wever, Eyke Hüllermeier"
permalink: /publication/2021-AutoCoevoRUL-Gecco
collection: publications
date: 2021-06-26
venue: "Proceedings of the Genetic and Evolutionary Computation Conference (GECCO'21)"
arxiv: 
paperurl: "https://dl.acm.org/doi/abs/10.1145/3449639.3459395"
code: "https://github.com/tornede/AutoCoevoRUL"
talk: 
slides: 
poster: 
blogpost: 
abstract: "Automated machine learning (AutoML) strives for automatically constructing and configuring compositions of machine learning algorithms, called pipelines, with the goal to optimize a suitable performance measure on a concrete learning task. So far, most AutoML tools are focused on standard problem classes, such as classification and regression. In the field of predictive maintenance, especially the estimation of remaining useful lifetime (RUL), the task of AutoML becomes more complex. In particular, a good feature representation for multivariate sensor data is essential to achieve good performance. Due to the need for methods generating feature representations, the search space of candidate pipelines enlarges. Moreover, the runtime of a single pipeline increases substantially. In this paper, we tackle these problems by partitioning the search space into two sub-spaces, one for feature extraction methods and one for regression methods, and employ cooperative coevolution for searching a good combination. Thereby, we benefit from the fact that the generated feature representations can be cached, whence the evaluation of multiple regressors based on the same feature representation speeds up, allowing the evaluation of more candidate pipelines. Experimentally, we show that our coevolutionary strategy performs superior to the baselines."
---
