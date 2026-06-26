---
title: "A Simulation Study of Topic Model Performance under Varying Corpus Conditions"
collection: working papers
category: manuscripts
permalink: /publication/2025-simulation-topic-models
excerpt: 'Monte Carlo simulation study examining how corpus characteristics affect LDA estimation performance, and comparing LDA and STM under temporally evolving topic prevalence. Presented as a poster at BaYSM 2025.'
date: 2025-06-01
venue: 'Bayesian Young Statisticians Meeting (BaYSM 2025), Chiba, Japan'
citation: 'Medeiros, C., Quigley, J. & Revie, M. (2025). A simulation study of topic model performance under varying corpus conditions. Poster presented at BaYSM 2025, Chiba, Japan.'
---

Topic models such as Latent Dirichlet Allocation (LDA) are widely used to uncover latent thematic structure in text corpora. Despite their extensive application, limited practical guidance exists on the corpus conditions under which these models yield reliable estimates — particularly for small corpora or short documents.

This paper addresses this gap through a two-part Monte Carlo simulation study. The first part examines how document length, corpus size, vocabulary size, number of topics, and Dirichlet prior settings jointly influence the bias and RMSE of LDA's per-document topic proportion estimates. Results show that LDA produces essentially unbiased estimates across all settings considered, with RMSE decreasing rapidly as document length increases, stabilising around 200–250 words. Corpus size and vocabulary size also play important roles in estimation precision.

The second part compares LDA and the Structural Topic Model (STM) in settings where topic prevalence changes over time. Contrary to the assumption that STM's explicit modelling of temporal covariates confers a general advantage, we find a crossover effect: STM outperforms LDA for short documents, but for documents longer than approximately 200 words, LDA achieves comparable or lower RMSE across a wide range of conditions.

The findings provide actionable guidance for practitioners applying topic models in small-sample or temporally evolving corpus settings.

*Joint work with John Quigley and Matthew Revie (University of Strathclyde). Presented as poster at BaYSM 2025. Work in progress.*
