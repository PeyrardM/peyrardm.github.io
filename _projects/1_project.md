---
layout: page
title: Causal Machine Learning
description: Taking the problem of causation versus correlation at its root
img: assets/img/12.jpg
importance: 1
category: work
related_publications: einstein1956investigations, einstein1950meaning
---

Machine learning is a powerful computational approach that seeks to uncover and model statistical relationships within observed data.
Machine learning algorithms are designed to learn from historical data and use these learned statistical patterns to make informed prediction about future outcomes. The usefulness of this approach relies on the assumption that the data points are, and will be, independent and identically distributed (i.i.d.).

In practice, data rarely follows the i.i.d assumption. Real-world data is dynamic, subject to changes, and often influenced by various contextual factors and temporal dependencies. In such a dynamic context, purely predictive models are thus bound to fail.

To move past the limitations of the statistical learning paradigm, we need to use the language of causality. Causal machine learning goes beyond the "what" and focuses on answering the "why" behind the data and the "what if" by modeling the mechanistic processes that generate it. Causal thinking forces us to acknowledge that it is not just about identifying patterns; it's about understanding the driving forces behind those patterns. Causal modeling opens doors to profound insights, informed decision-making, and a more nuanced comprehension of the complex data we observe. This perspective opens up a whole new world of possibilities and challenges:

#### 1. Causal Inference
Causal modeling deals with "why" behind data patterns, providing a deeper understanding of the driving forces behind the observed data in the world, helping make choices for future interventions.

#### 2. Out-Of-Distribution Generalization:
By removing spurious correlations and focusing on causal relationships, models can perform far out of their training distribution.

#### 3. Fairness & Counterfactuals
Ensuring fairness in machine learning models is a critical concern. Causal modeling enables us to explore counterfactual fairness, where we assess what would have been the outcome had some individual characteristics been different.

#### 4. Causal Discovery
Uncovering the causal mechanisms that generate the data is the great challenge of causal discovery. It is in general impossible to do from observed data alone, but it is the subject of a promising research direction.

#### 5. Evaluation
The world is full of situations that violate the i.i.d. assumption. Causal language is essential to distinguish between various types of non-i.i.d. data and evaluate how machine learning models perform under different conditions.
