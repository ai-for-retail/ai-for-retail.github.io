---
layout: page
title: "Software"
permalink: /software/
order: 5
---

### Serenade

Serenade is a scalable session-based recommendation system, which is in production usage by our industry partners. Serenade has been developed in a collaborative effort between AIRLab Amsterdam and bol.com. Serenade is tailored towards recommending the next product to view for users in an e-commerce setting and handles scenarios with millions of items to recommend and hundreds of millions of historical clicks to learn from.

It provides the following advantages over existing frameworks:
 * Rust-based inference server providing millisecond-latency responses.
 * Battle-tested with up to 1000 requests per second.
 * Support for de-personalised recommendations.
 * Support for automated hyperparameter tuning.
 * Deployable via Docker and Kubernetes.

Serenade will be made available soon.


### Probabilistic Gradient Boosting Machines (PGBM) 

Probabilistic Gradient Boosting Machines (PGBM) is a probabilistic gradient boosting framework in Python based on PyTorch/Numba. It is aimed at users interested in solving large-scale tabular probabilistic regression problems, such as probabilistic time series forecasting. It provides the following advantages over existing frameworks:

 * Probabilistic regression estimates instead of only point estimates.
 * Auto-differentiation of custom loss functions.
 * Native GPU-acceleration.
 * Distributed training for CPU and GPU, across multiple nodes.
 * Ability to optimize probabilistic estimates after training for a set of common distributions. 

PGBM is available at [https://github.com/elephaint/pgbm](https://github.com/elephaint/pgbm).
